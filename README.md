# Java Swing Chess Game

A desktop Chess application built in **Java** using **Swing (`JFrame`, `JPanel`, `JButton`)** for the user interface and a modular game engine for board state, piece movement validation, and special moves.

## Project Structure

- `ChessGameUI.java` — Swing GUI (`8x8` board grid, turn selection, square highlighting, and piece rendering).
- `ChessGameEngine.java` — Core game loop, turn management, board initialization, move execution, and check validation.
- `PieceValidation.java` — Movement rules and path-clearing checks for Pawn, Rook, Knight, Bishop, Queen, and King.
- `SpecialMoves.java` — Handlers for castling, pawn promotion (defaults to Queen), en passant capture, check detection, and checkmate checks.

## Prerequisites

- **Java Development Kit (JDK)** (JDK 17 or newer recommended)
- **Git** (for version control and pushing to GitHub)

## How to Compile and Run

Open a terminal inside the project directory and run:

```bash
javac *.java
java ChessGameUI