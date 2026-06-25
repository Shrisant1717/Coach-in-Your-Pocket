# Coach in Your Pocket: AI-Powered Cricket Analytics Platform

## Overview

Coach in Your Pocket is an AI-driven cricket analytics platform that leverages computer vision and deep learning to automatically analyze cricket match videos. The system provides actionable performance insights through ball tracking, bowling heatmaps, wagon wheel visualizations, and trajectory analysis, helping players, coaches, and analysts make data-driven decisions.

---

## Features

### Cricket Video Analysis

* Upload and analyze cricket match videos.
* Automatic detection and tracking of players and cricket balls.
* Real-time video processing using computer vision.

### Bowling Heatmaps

* Visualize ball pitching locations.
* Identify bowling patterns and strengths.
* Analyze line and length consistency.

### Wagon Wheel Analysis

* Generate shot distribution visualizations.
* Understand batter scoring patterns.
* Analyze scoring areas and strike zones.

### Ball Trajectory Tracking

* Track ball movement frame-by-frame.
* Visualize ball paths for performance analysis.
* Support LBW and bowling assessment scenarios.

### Player Detection

* Detect players on the field using object detection models.
* Monitor player positioning and movement.

### Interactive User Interface

* Simple drag-and-drop video upload.
* Automated report generation.
* Interactive visual analytics dashboard.

---

## System Architecture

1. **Video Upload**

   * User uploads cricket match footage.

2. **Object Detection**

   * YOLOv8 detects players and cricket balls.

3. **Tracking Module**

   * Tracks ball movement across frames.

4. **Analytics Engine**

   * Generates heatmaps.
   * Creates wagon wheel visualizations.
   * Computes trajectory data.

5. **Visualization Layer**

   * Displays analytics and performance insights.

---

## Tech Stack

* Python
* YOLOv8
* Ultralytics
* OpenCV
* NumPy
* Pandas
* Streamlit
* Matplotlib

---

## Project Structure

```text
Coach-In-Your-Pocket/
│
├── app.py
├── requirements.txt
├── models/
│   └── yolov8_model.pt
│
├── videos/
│   └── sample_matches/
│
├── outputs/
│   ├── heatmaps/
│   ├── wagon_wheels/
│   ├── trajectories/
│   └── reports/
│
└── README.md
```

---

## Key Capabilities

* Automated cricket video analysis.
* Ball and player detection using YOLOv8.
* Bowling heatmap generation.
* Wagon wheel visualization.
* Ball trajectory tracking.
* Performance analytics dashboard.

---

## Applications

* Cricket Coaching
* Performance Analysis
* Match Strategy Planning
* Player Development
* Sports Analytics Research
* Cricket Academies and Training Centers

---

## Results

The platform automatically transforms raw cricket footage into meaningful insights by generating:

* Bowling Heatmaps
* Wagon Wheel Visualizations
* Ball Trajectory Analysis
* Player Detection Reports

These analytics help coaches and players evaluate performance without manual video review.

---

## Future Enhancements

* Batting stance analysis
* Bowling action assessment
* Player performance prediction
* Multi-camera tracking support
* Mobile application deployment
* Real-time match analytics

---

## Author

**Shrisant Barate**

Artificial Intelligence & Data Science Engineer

Focused on Computer Vision, Sports Analytics, Machine Learning, and Agentic AI Systems.
