# 🖌️ Virtual Paint with OpenCV

This project contains two OpenCV-based tools:

-  **Virtual Paint**: Track objects of specific colors in real time and draw on the screen using your webcam.
-  **Color Picker**: Dynamically select HSV color ranges to tune detection thresholds.

---

##  Features

### Virtual Paint
- Tracks predefined color ranges in real time.
- Draws virtual strokes based on the detected object's position.
- Uses HSV color space and contours to identify object centers.

### Color Picker
- Interactive HSV sliders to calibrate color ranges.
- Real-time mask and result visualization to fine-tune thresholds.
- Outputs HSV values that can be used in `Virtual Paint`.

---

## Installation

Make sure you have Python and OpenCV installed:

