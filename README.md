# Multi-Directional Moving Balls Animation

This project creates multiple balls that move in various directions across the screen: top-down, bottom-up, left-right, and right-left. The balls bounce back upon hitting the edges of the viewport.

## Technologies Used
- **HTML5**: To structure the webpage.
- **CSS**: For styling the moving elements (balls).
- **JavaScript**: Handles the movement logic for the balls.

## Features
- Four sets of balls:
  1. Top-Down: Moves vertically from top to bottom.
  2. Bottom-Up: Moves vertically from bottom to top.
  3. Left-Right: Moves horizontally from left to right.
  4. Right-Left: Moves horizontally from right to left.
- Each ball is randomly assigned a position and speed.
- Balls change direction (bounce) upon hitting the screen's boundary.
- Balls are dynamically created and assigned random colors.

## How to Use
1. Clone or download the repository.
2. Open the `index.html` file in any modern browser.
3. Watch the animated balls move in different directions!

## Code Breakdown

- **Ball Creation**: 
  - The `create()` function dynamically generates `div` elements representing balls.
  - Each ball is randomly assigned a color from a predefined palette.

- **Ball Movement**: 
  - Arrays store the balls and their positions
