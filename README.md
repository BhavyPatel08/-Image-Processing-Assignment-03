Image Processing – Lab 9 & 10 (Assignment 03)

About the Project

This repository contains my Lab 9 and Lab 10 Image Processing assignment, implemented in Python using a Jupyter Notebook.

It includes 6 required lab problems and 4 additional problems, covering various Digital Image Processing techniques.

Notebook

* Assignment_03.ipynb – Complete notebook containing code, explanations, visualisations, and evaluation metrics.

Problems Covered

1. Comparative Edge Detection
2. Noise Sensitivity Analysis
3. Run-Length Encoding (RLE) vs. Huffman Coding
4. JPEG Block Artifacts using 8×8 DCT, Quantisation, and IDCT (PSNR and SSIM)
5. GLCM Texture Segmentation
6. Multi-Feature Leaf Segmentation

Additional Problems

7. Histogram Equalisation vs. CLAHE
8. Comparison of Mean, Gaussian, Median, and Bilateral Denoising Filters
9. Global, Otsu, and Adaptive Thresholding
10. Frequency-Domain Filtering using 2D FFT

Technologies & Libraries Used

* Python
* OpenCV
* NumPy
* Matplotlib
* Scikit-image
* Scikit-learn
* Requests
* Google Colab / Jupyter Notebook

How to Run

Google Colab

1. Open Google Colab.
2. Upload Assignment_03.ipynb.
3. Run all cells sequentially from top to bottom.
4. Allow the notebook to download the required sample images.

Local Jupyter Notebook

1. Download or clone this repository.
2. Install the required libraries.
3. Open Assignment_03.ipynb.
4. Execute all cells sequentially.

Installation

Install the required dependencies:

pip install opencv-python numpy matplotlib scikit-image scikit-learn requests

Important Notes

* An active internet connection is required to download sample images from Wikimedia Commons.
* The notebook automatically creates an images/ folder.
* Image source and licence details are saved in images/sources.csv.
* Some computations, particularly GLCM texture segmentation, may take additional time depending on the system.
* Increasing the STEP value can help speed up GLCM processing.
* The notebook generates output files inside the outputs/ folder.
* A ZIP archive named lab_outputs.zip is generated containing the output files.
* Run the notebook sequentially to avoid missing variables or files.
* Leaf segmentation is a demonstration technique and is not a scientifically validated diagnostic method.

Author

Bhavy Patel

⸻

Submitted as part of the academic coursework in Digital Image Processing.
