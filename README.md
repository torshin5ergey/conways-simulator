# John Conway's Game of Life with p5.js

Conway's famous cellular automaton "Game of Life" in JavaScript using p5.js.

![demo](assets/demo.gif)

## Description

Conway's [Game of Life](https://en.wikipedia.org/wiki/Conway's_Game_of_Life) is a cellular automaton devised by the British mathematician John Horton Conway in 1970. The simulation consists of a grid of cells, each of which can be in one of two states: alive or dead. At each step of the simulation, cells transition between these states according to certain rules.

## Rules

1. **Survival:** A live cell survives if it has 2 or 3 neighbors (other live cells). Otherwise, it dies due to "loneliness" or "overcrowding".
2. **Birth:** An empty (dead) cell with exactly 3 live neighbors becomes alive.

## How to Run

1. Open `index.html` in your web browser.
2. Upon startup, a random field of cells will be generated.
3. The simulation will run indefinitely, with cells evolving according to the rules.

## View Online

You can also view this project online [here](https://editor.p5js.org/torshin5ergey/full/GNVlnPY3O)

## How to Use in Your Project

1. Clone the repository to your computer.
2. Include `p5.js` in your project.
3. Import `sketch.js` into your project and use it in your code.

## License

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Author

Sergey Torshin [@torshin5ergey](https://github.com/torshin5ergey)
