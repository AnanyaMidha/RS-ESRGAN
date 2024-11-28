# RS-ESRGAN
 Remote Sensing Enhanced Super-Resolution GAN
This project implements the Enhanced Super-Resolution Generative Adversarial Network (ESRGAN) for super-resolution of Sentinel-2 satellite images. By enhancing low-resolution imagery, RS-ESRGAN bridges the gap between the free availability of Sentinel-2 data and the high-resolution requirements of various remote sensing applications.

Features
Uses ESRGAN architecture, tailored for multi-spectral satellite imagery.
Removes upsampling layers for co-registered images, ensuring compatibility with remote sensing datasets.
Processes four channels (RGB + Near Infrared) for enhanced spectral fidelity.
Achieves significant improvement in resolution while preserving spatial and spectral information.
Validated using metrics like PSNR, SSIM, and qualitative visual analysis.

Dataset
This project uses paired datasets of low-resolution Sentinel-2 and high-resolution WorldView imagery. Preprocessed data is required for training.

Results
Quantitative results:

PSNR: +2.5 dB over baseline.
SSIM: Improved by 15%.
Qualitative improvements include better edge details and spectral consistency.


