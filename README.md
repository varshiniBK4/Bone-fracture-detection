# 🦴 Bone Fracture Detection Using Digital Image Processing

## 📌 Project Overview

This project demonstrates digital image processing techniques applied to hand and wrist X-ray images. It explores image filtering, contrast enhancement, and segmentation methods to improve the visibility of bone structures and potential fracture regions.

The project uses Python and OpenCV to process X-ray images and compare the results of different image processing techniques.

## 🎯 Objectives

* Reduce noise in X-ray images.
* Improve image contrast and visibility of bone structures.
* Apply segmentation techniques to identify image regions and boundaries.
* Compare different digital image processing methods.
* Explore how image processing can support medical image analysis.

## 🛠️ Technologies Used

* Python
* OpenCV
* NumPy
* Matplotlib
* Jupyter Notebook

## 🔬 Image Processing Techniques

### 1. Noise Filtering

* **Median Filter:** Reduces salt-and-pepper noise while preserving edges.
* **Gaussian Filter:** Smooths images to reduce random noise.
* **Bilateral Filter:** Reduces noise while preserving important edges.

### 2. Contrast Enhancement

* **Histogram Equalization:** Improves overall image contrast.
* **CLAHE:** Enhances local contrast while limiting excessive enhancement.

### 3. Image Segmentation

* **Thresholding:** Separates pixels according to intensity.
* **Canny Edge Detection:** Highlights image boundaries and intensity changes.
* **Watershed Segmentation:** Divides images into regions using boundary markers.

## 🔄 Project Workflow

1. Load a grayscale hand or wrist X-ray image.
2. Apply noise filtering techniques.
3. Enhance contrast using Histogram Equalization and CLAHE.
4. Apply Thresholding, Canny Edge Detection, and Watershed Segmentation.
5. Visualize and compare the processed images.
6. Save the processed outputs for further analysis.

## 📦 Installation

Install the required libraries:

```bash
pip install opencv-python numpy matplotlib jupyter
```

## 🚀 How to Run

1. Clone or download this repository.
2. Install the required Python libraries.
3. Place your permitted X-ray input image in the notebook's working directory.
4. Update the image filename in the notebook if necessary.
5. Open the Jupyter Notebook.
6. Run the cells in order to view and save the results.

## 📊 Expected Outputs

* Original X-ray image
* Median-filtered image
* Gaussian-filtered image
* Bilateral-filtered image
* Histogram-equalized image
* CLAHE-enhanced image
* Thresholding result
* Canny edge detection result
* Watershed segmentation result

## ⚠️ Limitations

* Processing results depend on image quality and parameter settings.
* Segmentation may not accurately isolate bones or fracture regions.
* Highlighted edges are not necessarily fractures.
* This project does not establish a clinically validated automated fracture detection model.

## 🔮 Future Scope

* Use a suitable labelled X-ray dataset.
* Develop a machine learning or deep learning model for fracture classification.
* Evaluate performance using appropriate metrics such as precision, recall, sensitivity, and accuracy.
* Explore fracture localization and segmentation using validated methods.

## 👩‍💻 Author

Varshini.BK

## 📝 Disclaimer

This project is for educational and research purposes only. It is not intended to diagnose fractures or replace professional medical evaluation.
