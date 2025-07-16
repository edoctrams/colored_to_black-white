#  Grayscale Image Converter (Python + OpenCV)

This is a simple Python project that converts a **color photo to grayscale** using the OpenCV library.

---

##  Features

- Loads a color image
- Converts it to grayscale
- Saves the result as a new image
- Works in Jupyter Notebook or as a standalone Python script

---

##  How It Works

1. Load the input image using `cv2.imread()`
2. Convert it to grayscale using `cv2.cvtColor()`
3. Save the output using `cv2.imwrite()`

---

## ▶ How to Run

1. Place your image file (e.g. `input.jpg`) in the project folder
2. Run the Python script or notebook

### Example:
```python
import cv2

image = cv2.imread("input.jpg")  # Replace with your image file
gray_image = cv2.cvtColor(image, cv2.COLOR_BGR2GRAY)
cv2.imwrite("output_gray.jpg", gray_image)
print("✅ Image successfully converted to grayscale.")


