# 📷 Motion Detection Snapshot System

A **real-time motion detection system** built using Python and OpenCV. The program uses a webcam to continuously monitor a live video feed. When motion is detected in the frame, it captures a snapshot with a timestamp and stores it locally. The system also includes a cooldown timer to prevent excessive snapshot capturing, making it practical for surveillance purposes.

---

## 🛠 Features

- ✅ Real-time webcam feed monitoring
- 🎯 Motion detection using frame differencing
- 🕒 Cooldown timer between snapshots to avoid redundant captures
- 🧠 Smart filtering of small/noise movements using contour area
- 🖼️ Automatically saves images with timestamp overlays
- 📁 All snapshots organized into a `Captured` folder

---


---

## 🚀 Getting Started

### 🔧 Prerequisites

Make sure you have the following installed:

- Python 3.x
- OpenCV (`cv2` library)

### 📦 Installation 

1. Clone this repository or download the code.
2. Install dependencies:

```bash
pip install opencv-python

Run the script using:
python motion_detector.py

Or, if using Jupyter Notebook, just run the cell.


