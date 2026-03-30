# Sudoku Solver

A Python-based project that models Sudoku with set theory and solves puzzles the way a human would approach one - with logic and solving techniques instead of brute force.
Performance and solving time is not of importance here, rather than the step by step solution path.

## What it does

- Represents each empty cell with a candidate set
- Applies solving strategies in sequence
- Tracks both:
  - digit placements
  - candidate eliminations
- Visualizes the solving process

## Implemented strategies

- Naked Singles
- Hidden Singles
- Naked Pairs / Triples
- Hidden Pairs / Triples
- Pointing Pairs / Triples
- Box-Line Reduction
- X-Wing
- Y-Wing
- Swordfish
- Skyscraper

## Outputs

- **List of steps**
  - prints the action applied (technique and affected cell)
  - prints the board in its final state

- **Animated board replay**
  - step-by-step digit placement and candidate elimination video  
  - red = digit placement
  - blue = candidate elimination

- **3D solution path**
  - X = column
  - Y = row
  - Z = solving step
