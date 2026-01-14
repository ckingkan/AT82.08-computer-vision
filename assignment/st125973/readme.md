# 🦖 Augmented Reality Dino Viewer – README

## 🔧 Controls

### 🎮 Keyboard Shortcuts

- `S` – Take snapshot (used for panorama or calibration)
- `P` – Create panorama from snapshots
- `K` – Start camera calibration (chessboard required)
- `G` – Toggle Grayscale mode
- `H` – Toggle HSV Hue channel view
- `E` – Toggle Canny Edge detection
- `L` – Toggle Hough Line detection
- `C` – Toggle Histogram display
- `X` – Toggle Transform controls
- `Q` – Quit

### 🎚️ Main Trackbars (`main_video` window)

- **Contrast / Brightness** – Adjust image appearance
- **Gaussian** – Apply Gaussian blur
- **Bilateral_d / sigmaColor / sigmaSpace** – Bilateral filter
- **Canny1 / Canny2** – Canny edge thresholds
- **Hough_thresh** – Hough line detection threshold

### 🧭 Transform Trackbars (`Transform Controls` window)

- **Tx / Ty** – Translate image
- **Rotation** – Rotate image
- **Scale** – Resize image

## 📷 Features

### 🦖 AR Dinosaur

- Requires visible **9x6 chessboard** in camera view.
- Dinosaur wireframe is projected onto the board in real-time.

### 🖼️ Panorama

- Press `S` to capture 2+ frames
- Press `P` to generate panorama

### 🧪 Camera Calibration

- Press `K` to start.
- Hold chessboard for 10 timed captures.
- Calibration is displayed if successful.

### 📊 Histogram

- RGB or Grayscale histogram shown when enabled (`C`).

---

> ✅ Ensure `trex_model.obj` exists in the `assets/` directory.  
> ⏹️ Press `Q` to exit.
