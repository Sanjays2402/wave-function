# Wave Function Collapse 🌊

Interactive visualizer for the Wave Function Collapse algorithm. Watch as tiles are placed one by one with constraint propagation.

![Screenshot](screenshot.png)

## Features

- **Step-by-step mode** — Observe each collapse and propagation
- **Auto-play** — Watch the algorithm run at adjustable speed
- **Click to collapse** — Manually choose cells to collapse
- **Entropy visualization** — See which cells have the fewest options
- **Hover tooltips** — View entropy values and possible tiles for any cell
- **5 tile types** — Deep water, water, sand, land, forest
- **Adjacency rules** — Tiles can only neighbor compatible types
- **Contradiction tracking** — See when the algorithm hits dead ends

## How It Works

The Wave Function Collapse algorithm starts with every cell in a superposition of all possible tiles. At each step:

1. Find the cell with the lowest entropy (fewest options)
2. Collapse it to a random valid tile (weighted by neighbor compatibility)
3. Propagate constraints to neighboring cells
4. Repeat until all cells are collapsed

## Usage

Open `index.html` in any modern browser. No build step required.

## License

MIT
