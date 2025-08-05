## Introduction to Image Processing with Pillow (PIL)

**Image processing** refers to the techniques used to analyze, manipulate, and transform images. It plays a vital role in computer vision, pattern recognition, and machine learning. Common operations include resizing, color adjustments, filtering, and shape drawing — all used to enhance image quality or extract meaningful information.

This project uses **Python's Pillow (PIL)** library to demonstrate foundational image preprocessing techniques, ideal for beginners and those working on early-stage computer vision projects.


## Project Overview

This project is designed to explore core image processing operations using the **Pillow** library. Each section provides a practical task with corresponding code and output, focusing on visual understanding.

### Key Components of This Project:

1. ### **Image Loading and Property Extraction**

   * Load an image file using `Image.open()`
   * Display basic image attributes: **format**, **size**, and **mode**
   * Understand what the mode (e.g., `RGB`, `L`) represents in terms of color channels

2. ### **Displaying the Image**

   * Show the image inline using `IPython.display`
   * Useful for visual confirmation after each transformation

3. ### **Grayscale Conversion**

   * Convert a color image to grayscale using `ImageEnhance.Color` or `.convert("L")`
   * Understand how image **mode** and pixel information change post conversion

4. ### **Image Resizing**

   * Resize the image to custom dimensions like `200×200` using `resize()`
   * Save the resized output to a new file

5. ### **Drawing on the Image**

   * Use `ImageDraw.Draw()` to overlay **red rectangles** at various coordinates
   * Observe the visual impact of changing rectangle position and dimensions

## Tools and Libraries Used

* **Pillow (PIL)** – Image loading, enhancement, conversion, and drawing
* **IPython.display** – Inline image visualization
* **Matplotlib & Seaborn** – Additional visualization support (light use)
* **NumPy** – For potential array manipulation (imported, though minimally used)

## Use Cases

This project is perfect for:

* Students exploring the fundamentals of image preprocessing
* Developers preparing image data for computer vision or ML tasks
* Beginners learning to manipulate and transform images with code
* Anyone wanting a practical intro to the Pillow library
