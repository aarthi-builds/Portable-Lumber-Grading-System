# Portable Lumber Grading System
**Based on Acoustic Tomography and Vision Analysis**

## Project Overview
This project provides a portable solution for lumber grading by combining two advanced techniques:
1. **Acoustic Tomography:** Used for internal density and defect analysis.
2. **Vision Analysis:** YOLO-based computer vision for surface defect detection.

## Tech Stack
- **Vision:** YOLO (v8), OpenCV, PyTorch.
- **Acoustics:** Signal processing and tomography analysis.

## Files Description
- `data.yaml`: Dataset configuration.
- `yolov8n.pt` / `yolo26n.pt`: Pre-trained models for detection.
- `main.py`: Main execution script for the system.

## How to Setup & Run
1. Clone the repository:
   `git clone https://github.com/aarthi-builds/Portable-Lumber-Grading-System.git`
2. Install dependencies:
   `pip install ultralytics opencv-python`
3. Run the system:
   `python main.py`
