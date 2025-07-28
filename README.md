# Rubix-Cube

This is a web-based Rubik's Cube Solver that allows users to manually input the colors of all six faces of a Rubik's Cube, validates the input, and computes a solving algorithm using the Kociemba two-phase method (via cubejs).

 Features

 * Color Palette: Select from six standard cube colors (White, Yellow, Red, Orange, Green, Blue) with visual limits (9 tiles per color).

 * Face Selection: Choose one of the six cube faces (U, R, F, D, L, B) and paint it using a 3×3 editable grid.

 * Undo/Redo Support: Modify your inputs with undo and redo actions (up to 2 steps).

 * Clear & Reset: Clear the current face or reset the entire cube.

 * Solver Integration: After all faces are filled correctly, click "Submit" to generate the solving formula using standard cube notation (R, U, F, L, D, B).

 * Input Validation: Ensures each color is used exactly 9 times and center tiles are fixed.



  
  How It Works
1. Choose a color from the palette.

2. Select a face (Up, Right, Front, Down, Left, Back).

3. Click on stickers in the 3×3 grid to apply the selected color.

4. Repeat for all faces until every tile is filled correctly.

5. Click Submit to see the solving algorithm.