# 📷 OpenCV Lab: Computer Vision Playground

[`python`](https://github.com/topics/python) • [`opencv`](https://github.com/topics/opencv) • [`computer-vision`](https://github.com/topics/computer-vision) • [`image-processing`](https://github.com/topics/image-processing) • [`jupyter-notebook`](https://github.com/topics/jupyter-notebook) • [`haar-cascade`](https://github.com/topics/haar-cascade) • [`colab`](https://github.com/topics/colab)

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <a href="https://colab.research.google.com/github/pranataa-labs/OpenCV-Lab/blob/main/belajar-opencv.ipynb" target="_blank">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" style="height: 28px;"/>
  </a>
</p>

An interactive playground repository for mastering digital image processing and Computer Vision with **OpenCV** from fundamental pixel mechanics to advanced morphological analysis and real-time video stream processing.

---

## 📁 Image & Video Assets

- `pohon.jpg`: Master image for geometric transformations, spatial filtering, and contour extraction.
- `wajah.jpg`: Portrait image for validating face detection via *Haar Cascades*.
- `burung.jpg`: Silhouette asset for bitwise operations and channel isolation.
- `video.mp4`: Source video file for frame extraction and frame-by-frame processing.

---

## 📌 Curriculum & Core Learning Modules

- **OpenCV Fundamentals & I/O:** Reading images (`imread`), visualization (`cv2_imshow` / Matplotlib), file export (`imwrite`), image metadata (resolution & channels), pixel manipulation in BGR color space, and blank canvas generation.
- **Geometric Transformations & Drawing:** Spatial resizing (`resize`), cropping, 2D affine translation (`warpAffine`), rotation matrices, reflection flips (`flip`), drawing primitives (lines, rectangles, circles), and rendered typography (`putText`).
- **Color Spaces & Thresholding:** Grayscale conversion (`cvtColor`), HSV color space, channel splitting & merging, simple binary thresholding, adaptive Gaussian thresholding, Otsu's optimal thresholding, and color inversion.
- **Filtering, Blurring & Edge Detection:** Custom 2D convolution kernels, box averaging blur, Gaussian blur, median filtering, bilateral edge-preserving smoothing, Sobel gradients, Laplacian operator, and Canny edge detection.
- **Mathematical Morphology & Contour Analysis:** Structural erosion, dilation, morphological opening and closing, contour extraction (`findContours`), contour drawing (`drawContours`), bounding box fitting, and geometric area/perimeter calculation.
- **Advanced Features, Masking & Video Analytics:** Bitwise masking (AND, OR, XOR), color histogram computation, global histogram equalization, Contrast Limited Adaptive Histogram Equalization (CLAHE), multi-scale template matching, Haar Cascade face detection, video ingestion (`VideoCapture`), frame extraction, and video encoding (`VideoWriter`).

---

## 🚀 Execution & Setup Instructions

### Option A: Google Colab
Click the **Open in Colab** badge above or open `belajar-opencv.ipynb` directly in Google Colab.

### Option B: Local JupyterLab Environment
```bash
# Clone repository
git clone https://github.com/pranataa-labs/OpenCV-Lab.git
cd OpenCV-Lab

# Install dependencies
pip install -r requirements.txt

# Launch JupyterLab
jupyter lab
```

---

<p align="center">
  Crafted with precision by <a href="https://github.com/pranataa-labs"><b>pranataa-labs</b></a>.
</p>
