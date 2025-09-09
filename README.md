# WaveletVision

WaveletVision is a simple interactive tool to explore images using **wavelet decomposition** and **frequency-domain analysis**.  
Upload a grayscale image, pick a wavelet type, and view different sub-bands, energy, variance, and frequency spectra — all in one place.

## Features
- Upload any grayscale image.
- Perform multi-level (2-level) Discrete Wavelet Transform (DWT).
- Switch between multiple wavelets (Haar, Daubechies, Symlet, Coiflet, Biorthogonal).
- View approximation (LL) and detail (LH, HL, HH) sub-bands.
- Inspect both spatial (time-domain) and frequency-domain (FFT) views.
- Interactive sliders and dropdowns for easy exploration.

## Requirements
- Python 3
- Google Colab (recommended)
- Libraries:
  - `opencv-python`
  - `numpy`
  - `pywt`
  - `matplotlib`
  - `ipywidgets`
  - `PIL`

## How to Use (on Google Colab)
1. Open the Colab notebook or upload the script to Colab.
2. Run all cells to install and import dependencies.
3. Upload a grayscale image when prompted.
4. Use the dropdowns and sliders to switch wavelets, decomposition levels, and sub-bands.

## Use Cases
- Learn how wavelets analyze images at multiple resolutions.
- Visualize texture patterns and edges.
- Extract simple features (energy, variance) for classification tasks.
- Educational demonstrations in image processing courses.

---

> **Note:** Works best in Google Colab or Jupyter Notebook with `ipywidgets` enabled.


<img width="1338" height="777" alt="image" src="https://github.com/user-attachments/assets/1226f5cb-5412-4074-94f5-8dd7dccbd63c" />
