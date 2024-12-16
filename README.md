# -AI-Powered-One-Up-Puzzle-Solver

# Comparative Analysis of Object Tracking Algorithms

This repository contains the project **"Comparative Analysis of Object Tracking Algorithms: Mean Shift vs. CSRT"**, focused on evaluating and contrasting the performance of object tracking algorithms in dynamic environments. The work leverages Python, NumPy, and OpenCV libraries.

## Objective
To analyze and compare the effectiveness of the Mean Shift and CSRT (Discriminative Correlation Filter with Channel and Spatial Reliability) object tracking algorithms in handling dynamic scenarios, including scale changes, occlusion, and environmental variability.

## Key Features
- **Algorithm Implementation**: Mean Shift and CSRT trackers implemented using OpenCV.
- **Performance Evaluation**: Comparative study based on:
  - Tracking robustness
  - Computational efficiency
  - Adaptability to dynamic environments
- **Experimentation**:
  - Dynamic sequences with occlusion and scale changes
  - Static sequences for controlled evaluation

## Findings
- **CSRT Tracker**:
  - Superior in handling scale changes and occlusion.
  - More accurate in dynamic and complex environments.
- **Mean Shift Tracker**:
  - Efficient for simpler, static scenarios.
  - Limited adaptability to dynamic environments.

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: OpenCV, NumPy
- **Environment**: Configured for experimentation in both controlled and dynamic conditions.

## How to Run
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the scripts:
   ```bash
   python mean_shift_tracker.py
   python csrt_tracker.py
   ```

## Future Enhancements
- Expanding the analysis to include other trackers such as KCF, MOSSE, and TLD.
- Implementing real-time tracking scenarios with live video feeds.
- Enhancing visualization for better comparative insights.

## Contributions
Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit a pull request.

---

For more details, check out the project report or reach out via email.


