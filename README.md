# **Task 01: Color Image Analysis and Binary Conversion**

**Roll Number:** 2023-SE-06

### **Prompt**

*"Write a Python program using OpenCV and Matplotlib to do the following for a colored image uploaded in Google Colab:

* Read any colored image uploaded by the user.
* Display its Red, Green, and Blue components separately.
* Convert the image into a Grayscale image.
* Convert the image into a Binary image using Otsu's thresholding.
* Display all the images (Original, Red, Green, Blue, Grayscale, Binary) in a 2x3 subplot layout with appropriate titles and no axes.
* Ensure the code works in Google Colab and prompts the user to upload an image."*

---

## **Objective**

The objective of this task is to analyze a colored image by separating its Red, Green, and Blue components and to generate Grayscale and Binary versions. This demonstrates channel separation, intensity mapping, and thresholding in digital image processing.

---

## **Methodology / Approach**

1. User uploads a colored image in Google Colab using `files.upload()`.
2. Image is read with `cv2.imread()` and converted from **BGR to RGB** format.
3. RGB channels (Red, Green, Blue) are separated for individual analysis.
4. Image is converted to **Grayscale** using `cv2.cvtColor()`.
5. **Otsu's thresholding** is applied to create a **Binary** image.
6. All images are displayed using Matplotlib in a 2x3 subplot layout with appropriate titles and axes hidden.

---

## **Results / Observations**

* Red, Green, and Blue channels were visualized individually, showing how each color contributes to the image.
* Grayscale conversion preserved intensity information without color.
* Binary image effectively segmented foreground and background using Otsu's method.
* Visualization in a 2x3 layout allowed easy comparison of all results.

---

## **Tools and Libraries Used**

* **Python 3.x**
* **OpenCV (cv2)** for image reading, channel separation, and thresholding
* **Matplotlib (plt)** for visualization
* **Google Colab** for uploading and running the code

---
