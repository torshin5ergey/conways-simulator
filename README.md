# Conway's Game of Life with p5.js

Conway's famous cellular automaton "Game of Life" in JavaScript using p5.js.

![demo][assets/demo.gif]

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

This project is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/).

## Author

[Sergey Torshin] - [https://github.com/torshin5ergey]
