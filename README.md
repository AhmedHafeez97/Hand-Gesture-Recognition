A Project Assignment as a part of course work NIU MEE 623 - Robot Vision Control

# Hand Gesture Recognition 

Welcome to the **Hand Gesture Recognition** project! 🚀 This Python-based application uses a live camera feed to recognize hand gestures based on finger positioning. It's designed to detect gloves within a defined region of interest (ROI), calculate Euclidean distances between key points, and map these metrics to pre-programmed gestures. 

---

## Features 

- **Dynamic Gesture Recognition**: Real-time recognition of programmed hand gestures based on the distance between fingers.
- **Region of Interest (ROI)**: Focused detection within a specific area to enhance accuracy and performance.
- **Customizable Gestures**: Easily add or modify gestures by programming new labels and poses.
- **Lightweight and Fast**: Built with Python and optimized for speed and efficiency.
- **Camera Integration**: Seamlessly integrates with any standard camera.

---

## How It Works 🛠

1. **Region of Interest**: The camera feed defines a specific ROI where hand gestures will be detected.
2. **Glove Detection**: The system looks for gloves to ensure high-contrast detection against the background.
3. **Euclidean Metrics**: Key points between fingers are calculated using the Euclidean distance formula.
4. **Gesture Mapping**: Pre-programmed gestures are identified based on the measured distances and labeled accordingly.

---

## Installation 

### Prerequisites
- Python 3.8 or later
- OpenCV
- Numpy
- Matplotlib (Optional, for visualization)

### Steps to Install

1. Clone the repository:
2. Install Prerequisites:
3. Run the script:
   ```bash
   python HandGestureRecognition.py
   ```
