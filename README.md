# AI-Based Squash Match Analysis System

A computer vision project that analyzes squash match videos to extract player movement and court positioning using deep learning and video processing techniques.

The system converts raw squash match footage into structured positional data that can be used for player movement analysis and tactical insights.

---

## Features

- Court keypoint detection using CNN models  
- Player position estimation from match videos  
- Mapping player positions onto a calibrated squash court  
- Visualization of player trajectories and movement patterns  

---

## Tech Stack

- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Matplotlib  

---

## Project Structure
squash-ai-analysis
│
├── notebooks
│ ├── baseline_court_keypoints.ipynb
│ ├── baseline_court_positions.ipynb
│ └── positions_superposition.ipynb
│
├── docs
│ └── Core Computer Vision Engine.pdf
│
├── models
├── data
├── requirements.txt
└── README.md



---

## Current Pipeline
Video Input
↓
Frame Extraction
↓
Court Keypoint Detection
↓
Player Position Estimation
↓
Court Coordinate Mapping
↓
Movement Visualization




---

## Future Work

- Ball detection and tracking  
- Rally segmentation  
- Shot classification  
- Movement heatmaps and tactical analytics  
- Interactive performance dashboard  

---

## Author

Dipendra Pratap Singh  
IIT Kanpur
