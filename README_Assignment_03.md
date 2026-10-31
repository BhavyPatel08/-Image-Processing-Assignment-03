# Image Processing – Lab 9 & 10 (Assignment 03)

This repository contains my Lab 9 and Lab 10 image-processing assignment, implemented in Python using a Jupyter Notebook. It includes **6 required lab problems and 4 additional problems**.

## Notebook

- `Assignment_03.ipynb` – Complete notebook with code, explanations, visualisations, and evaluation metrics.

## Problems Covered

1. Comparative edge detection
2. Noise sensitivity
3. Run-Length Encoding (RLE) vs. Huffman coding
4. JPEG block artifacts using 8×8 DCT, quantisation, and IDCT (PSNR and SSIM)
5. GLCM texture segmentation
6. Multi-feature leaf segmentation
7. **Extra:** Histogram equalisation vs. CLAHE
8. **Extra:** Comparison of mean, Gaussian, median, and bilateral denoising filters
9. **Extra:** Global, Otsu, and adaptive thresholding
10. **Extra:** Frequency-domain filtering using 2D FFT

## Tools and Libraries

- Python
- OpenCV
- NumPy
- Matplotlib
- scikit-image
- scikit-learn
- Requests

## How to Run

**Google Colab**
1. Open Google Colab.
2. Upload `Assignment_03.ipynb`.
3. Run the cells from top to bottom.
4. Allow the notebook to download the required sample photographs when prompted by the code.

**Jupyter Notebook (local)**
1. Download or clone this repository.
2. Install the required libraries (see below).
3. Open `Assignment_03.ipynb` and run all cells in order.

Install dependencies:

```bash
pip install opencv-python numpy matplotlib scikit-image scikit-learn requests
```

## Important Notes

- An internet connection is required for the automatic sample-image download from Wikimedia Commons.
- The notebook creates an `images/` folder and saves image source and licence details in `images/sources.csv`.
- If a downloaded image is unsuitable, follow the notebook instructions to select another candidate or optionally upload your own image.
- Some computations, particularly GLCM texture segmentation, may take around a minute or longer depending on the runtime. The notebook notes that increasing `STEP` can make this section faster.
- The final section creates a ZIP archive named `lab_outputs.zip` containing the generated files in the `outputs/` folder.
- Run the notebook sequentially so that required images, variables, and output folders are created before later problems execute.
- Leaf segmentation is a heuristic demonstration only; it is not a medically or scientifically validated diagnosis.

## Author

**Bhavy Patel**

---

*Submitted as part of the academic coursework.*
