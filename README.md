# Vehicle Tracking and Counting with YOLOv8

## Overview
This Jupyter notebook project uses YOLOv8 for vehicle tracking and implements a line crossing detection algorithm. The system counts vehicles that cross a specified line in a video, annotates the frames, and generates an output video with visualizations.

## Dependencies
- OpenCV
- Ultralytics YOLO
- supervision


## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/shaadclt/Vehicle-Counter-YOLOv8.git
   cd Vehicle-Counter-YOLOv8
   ```

## Usage

1. Open the Jupyter notebook:
  ```bash
  jupyter notebook
  ```

2. Run the **'vehicle_counter.ipynb'** notebook.


## Configuration

- Adjust line coordinates: **'START'** and **'END'** in the notebook.
- Configure YOLOv8 model parameters as needed.


## Results

The output video output_single_line.mp4 will be generated with annotated frames showing object tracks and the count of objects that crossed the line.


## Acknowledgements

- This project uses the YOLOv8 model from Ultralytics.
  


