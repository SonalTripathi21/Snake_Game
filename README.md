# Snake_Game
 Description:
The Snake Game is a simple console-based game developed in C language, where the player controls a snake to collect food and avoid collisions with the wall or its own body. This project is implemented in a text-based environment (no graphics or background image) using standard libraries, and it runs in the terminal/command prompt.

🎯 Objective:
To build a basic console game using C programming.

To understand the concepts of loops, conditionals, arrays, and real-time input handling.

To learn how to implement game mechanics such as movement, collision, and scoring.

🧰 Tools & Technologies Used:
Language: C

IDE: Code::Blocks / Turbo C / Visual Studio Code (or any C compiler)

Libraries: <stdio.h>, <conio.h>, <windows.h> (or <unistd.h> for Linux)

🌟 Key Features:
Snake moves in 4 directions using arrow keys or W, A, S, D.

Food appears randomly on the screen.

Score increases as the snake eats food.

Game over when snake collides with wall or itself.

No external graphics or background images — runs purely in console.

⚙️ How It Works:
The game area is printed using characters like #, *, or spaces to represent walls, food, and the snake.

The snake is represented by a series of coordinates stored in an array.

A loop continuously updates the snake's position, takes keyboard input using getch(), and refreshes the screen.

When the snake's head coordinates match the food coordinates, the score increases and the snake length grows.

If the snake hits the border or itself, the game ends and the final score is displayed.

✅ Learning Outcomes:
Gained hands-on experience with arrays, loops, and functions in C.

Learned how to simulate real-time behavior using logic and delays.

Improved understanding of console-based game design and basic UI.

Practiced writing modular, structured code in a low-level language.
