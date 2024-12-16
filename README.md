# AI Powered One-Up Puzzle Solver

This repository contains the project **AI Powered One-Up Puzzle Solver**, which uses artificial intelligence to solve the logic-based "One-Up Puzzle" game. The puzzle is solved using backtracking and forward propagation techniques, enhanced by visualization tools.

## Abstract
The "One-Up Puzzle" is played on an `n x n` grid containing walls, blocks, and valid cells. The objective is to assign numbers to valid cells while adhering to constraints in segmented regions. The project employs:
- **Backtracking** for exploring possible assignments.
- **Forward Propagation** for reducing the solution space.
- **Visualization Tools** to represent the grid and solution.

This project explores constraint satisfaction problems (CSPs) and demonstrates computational methods for solving structured problems in both recreational and real-world scenarios.

We are solving the puzzle from [One-Up Puzzle](https://www.oneuppuzzle.com/).

## Methodology
1. **Puzzle Representation**:
   - Grids are encoded into string representations for computational efficiency.
     - `gamestr_h` for horizontal details (rows).
     - `gamestr_v` for vertical details (columns).
   - Parsed strings are converted into numerical formats for algorithmic manipulation.
2. **Algorithms**:
   - **Backtracking**: Systematically assigns values to cells and retracts invalid assignments.
   - **Forward Propagation**: Reduces domains of adjacent cells for efficiency.
   - **Heuristics**: Prioritizes constrained cells to minimize computation.
3. **Visualization**:
   - Renders the puzzle grid, highlighting walls, blocks, and assigned values.
   - Color-coded numbers aid in interpretation and debugging.

## Challenges
- **Scalability**: Larger grids exponentially increase the solution space.
- **Complexity**: Parsing and converting diverse grid layouts.
- **Variability**: Handling diverse configurations while maintaining performance.

## Future Work
- **Image Processing Integration**:
  - Use OpenCV and OCR for grid input directly from images or screenshots.
  - Detect grid boundaries, walls, blocks, and numerical values automatically.
- **Interactive Solver**:
  - Real-time solving with improved visualization.
  - Enhance accuracy and speed of OCR processing.

## How to Use
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the solver:
   ```bash
   python one_up_solver.py
   ```
4. Visualize results:
   - Output includes grid state and solution representation.

## References
1. Simonis, H. (2005). Sudoku as a constraint problem.
2. Russell, S., & Norvig, P. (2020). Artificial Intelligence: A Modern Approach.
3. Knuth, D. E. (2000). Dancing links.
4. Korf, R. E. (1985). Depth-first iterative-deepening: An optimal admissible tree search.

## Contributors
- Dharanidhar Manne
- Cholayaswanth Kumar Golla
- Ravi Prasad Grandhi
- Sravya Reddy Kaitha
- Jitendra Kadiyam
