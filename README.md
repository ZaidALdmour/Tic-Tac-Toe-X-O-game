# Tic-Tac-Toe Desktop Game (Windows Forms)

An interactive, custom-designed Tic-Tac-Toe (X-O) desktop application built in C# using Windows Forms. This project showcases practical implementation of component state management, multi-conditional game matrix evaluation, and custom 2D vector drawing using the GDI+ Graphics interface.

## Features

* **Custom Board Rendering:** Grid lines are rendered smoothly using custom `Graphics.DrawLine` painting with adjusted width and rounding characteristics.
* **Matrix Win Detection:** Evaluates 8 separate winning paths (3 horizontal rows, 3 vertical columns, and 2 diagonals) immediately after each valid move.
* **Live Turn Tracker:** Dynamically manages switching control loops between Player 1 (X) and Player 2 (O).
* **Visual Win Indicator:** Automatically highlights the winning combination by changing the winning buttons' background color to Green-Yellow.
* **Draw & Progress Validation:** Counts valid placements continuously, correctly triggering a draw sequence if the matrix reaches maximum capacity without a winning path.
* **State Reset Engine:** Restores all assets, score buffers, tracking structures, and UI controls seamlessly without requiring an application restart.

## Tech Stack & Core Concepts Applied

* **Framework:** .NET Framework / Windows Forms
* **Language:** C#
* **Graphics API:** GDI+ via the `Form_Paint` event context (`Pen` and `Graphics` objects)
* **Data Constructs:** Custom tracking structures (`struct`) and structural game flags (`enum`)
* **Logic Management:** Input handling with resource mapping validation (`System.Resources`)

## How to Run
1. Clone the repository to your desktop.
2. Open the solution file inside Microsoft Visual Studio.
3. Build and Run the compiler sequence.
