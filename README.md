# Dicer

Dicer is a dice rolling game implemented in C. It allows players to roll different types of dice and keeps track of their scores and dice statistics.

## Features

- Roll six-sided dice
- Roll ten-sided dice
- Keep track of total points earned
- Track cumulative dice values
- Display frequency of rolled dice numbers
- Interactive graphical interface

## Requirements

- C compiler
- Graphics library (e.g., OpenGL, SDL, etc.) - Make sure to install the necessary libraries and link them with the code.

## Graphics Library (gfx.c and gfx.h)

Dicer uses the `gfx.c` and `gfx.h` files for graphical functionality. These files provide a simple interface for drawing shapes and text on the screen. Make sure to include these files in your project and link them properly.

You can find the `gfx.c` and `gfx.h` files in the "graphics" directory of this repository. If you're using a different graphics library, you may need to adjust the code accordingly.


## How to Run

1. Clone the repository:

   ```shell
   git clone https://https://github.com/adamkeidz/c-stuffs-I-did/
   ```
2. Compile the source code using a C compiler. Make sure to link the graphics library correctly:

   ```shell
   gcc -o dicer dicer.c -lgraphics
   ```
Replace -lgraphics with the appropriate flag for your chosen graphics library.

3. Run the executable:
   ```shell
   ./dicer
   ``` 
4. Follow the on-screen instructions to play the game and view statistics.

## Credits
Adam - Developer

---
