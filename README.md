# Image Deblurring

MATH 441 Project3 — 2025/26 W2

Image deblurring as an inverse problem, using a unified Tikhonov-FFT pipeline applied to three settings: linear motion blur, color image blur (including cross-channel coupling), and 3D volumetric blur. Naive inverse and Truncated SVD are included as baselines.

## Authors

- Umay Gokturk
- Tiffany Gong
- Luna Kim

## Requirements

- Python 3.x
- NumPy
- SciPy
- Matplotlib
- Pillow
- CVXPY

## Notebooks

- `motion_deblur_linear.ipynb` — Linear motion blur and deblurring
- `colorblurring.ipynb` — Color image blur and deblurring
- `3D_Blur/3D_blur.ipynb` — 3D volumetric blur and deblurring

## Usage

See individual notebooks for each blur type.
