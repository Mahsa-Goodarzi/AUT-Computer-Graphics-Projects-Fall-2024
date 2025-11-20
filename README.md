# Computer Graphics Course Projects (Fall 2024)

This repository contains a collection of practical assignments and projects developed for the **Computer Graphics** course at **Amirkabir University of Technology (Fall 2024)**.

The projects explore fundamental and advanced concepts of Image Processing using **Python**, **OpenCV**, **NumPy**, and **Matplotlib**. Each notebook focuses on specific techniques ranging from basic pixel manipulation to frequency domain analysis.

## Technologies Used
- **Python**
- **OpenCV** (cv2)
- **NumPy**
- **Matplotlib**
- **Pillow** (PIL)

## Project Overviews

### [Project 1: Introduction to OpenCV & Image Basics](./CG Project 1/CG_Project1.ipynb)
**Goal:** Getting started with image processing fundamentals.
- **Topics Covered:** Reading and displaying images, understanding color spaces (RGB vs BGR), accessing pixel values, Region of Interest (ROI), splitting/merging channels, and basic arithmetic operations on images.

### [Project 2: Image Compression & Formats](./CG Project 2/CG_Project2.ipynb)
**Goal:** Understanding image data representation and compression techniques.
- **Topics Covered:** Analysis of Lossy vs. Lossless compression (JPEG, PNG, TIFF, GIF), bit-plane slicing to visualize image depth, and basic downsampling techniques.

### [Project 3: Geometric Transformations](./CG Project 3/CG_Project3.ipynb)
**Goal:** Manipulating image geometry and perspective.
- **Topics Covered:** Implementation of Projective and Perspective transformations. Includes solving systems of linear equations to manually calculate the Homography matrix ($H$) for mapping source points to destination points.

### [Project 4: Histograms & Contrast Enhancement](./CG Project 4/CG_Project4.ipynb)
**Goal:** Analyzing and improving image visibility based on pixel intensity distributions.
- **Topics Covered:** Computing and plotting image histograms, analyzing dynamic range, and implementing local thresholding and contrast enhancement techniques to improve image quality.

### [Project 5: Spatial Filtering & Edge Detection](./CG Project 5/CG_Project5.ipynb)
**Goal:** Applying convolution kernels for noise reduction and feature extraction.
- **Topics Covered:** Implementation of a custom filter application function with padding support. Comparison between **Sobel** and **Canny** edge detection algorithms, and Gaussian blurring for noise reduction.

### [Project 6: Frequency Domain & Restoration](./CG Project 6/CG_Project6.ipynb)
**Goal:** Advanced processing using the Fourier Transform and non-linear filtering.
- **Topics Covered:** Implementation of **Median filters** (including decision-based variations) for noise removal. Using the **Fast Fourier Transform (FFT)** to analyze the frequency domain and perform image compression/reconstruction.

---

## How to Run
1. Clone the repository.
2. Ensure you have the required libraries installed:
   ```bash
   pip install opencv-python-headless numpy matplotlib pillow requests
