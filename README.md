# Line Connection and Direction Detection from Points

This project processes an image containing a series of lines, identifies the red and green points, and determines the connection order of the lines starting from the red point. It also extracts the direction of movement (e.g., `RIGHT`, `UP`, `LEFT`, `DOWN`) between the connected lines. Additionally, it handles cases where lines may appear reversed and filters out parallel or redundant lines.

## Features
- Detects red and green points from an image.
- Connects lines starting from the red point based on proximity to form a path.
- Handles lines in reverse order and ensures proper connection.
- Filters out parallel and redundant lines based on proximity.
- Identifies directions of movement (e.g., `RIGHT`, `UP`, `DOWN`, `LEFT`) between connected lines.
  
## Requirements
To run this project, you'll need the following Python libraries:
- `opencv-python`
- `numpy`
- `matplotlib`

You can install them using pip:

```bash
pip install opencv-python numpy matplotlib
