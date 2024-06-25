# CTU & IBM Quantum Hackathon 2024

## Quantum Maze Solver

This project demonstrates a quantum-inspired approach to solving a maze using quantum walks implemented with Qiskit. The maze is generated using a recursive backtracking algorithm, and the quantum walk simulates the traversal through the maze, with the path frequencies visualized using a heatmap.

### Dependencies

The project requires the following Python libraries:

- `numpy`
- `random`
- `matplotlib`
- `qiskit`
- `qiskit_aer`

You can install the required dependencies using pip:

```sh
pip install numpy matplotlib qiskit
```

### How to Run

1. Clone the repository:
```sh
git clone <repository-url>
cd <repository-folder>
```

2. Run the `maze_solver.py` script:
python maze_solver.py

### Code Overview

#### Maze Generation

The `Maze` class generates a maze using a recursive backtracking algorithm. The maze is represented as a 2D grid where walls are represented by `1` and paths by `0`. The entry point is at `(1, 0)` and the exit point is at `(height-2, width-1)`.

### Quantum Walk Solver
The `QuantumWalk2D` class performs the quantum walk using Qiskit. The walk is simulated using quantum circuits to determine the direction of movement.
