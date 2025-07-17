# MRI Denoise and Deblur

A collection of deep learning and classical algorithms for removing noise and blur from brain MRI scans. This project implements and evaluates five methods—DnCNN, CNN‑DMRI, RIDNet, U‑Net Lite, and Richardson–Lucy deconvolution—on synthetically corrupted MRI images, comparing their performance in terms of MSE, SSIM, and PSNR.

---

## 🚀 Features

- **Five Restoration Methods**  
  - **DnCNN**: Residual CNN for AWGN removal  
  - **CNN‑DMRI**: Encoder–decoder network for Rician noise  
  - **RIDNet**: Residual‑in‑Residual Dense Network with Feature Attention  
  - **U‑Net Lite**: Lightweight U‑Net variant  
  - **Richardson–Lucy**: Classical deconvolution baseline  

- **Dataset Preparation**  
  - Public Kaggle brain MRI dataset  
  - Four classes: glioma, meningioma, pituitary tumor, no tumor  
  - Artificial motion blur and AWGN (σ = 0.15) applied  

- **Evaluation**  
  - Quantitative metrics: MSE, SSIM, PSNR  
  - Qualitative comparisons: example triplets and histograms  
  - Two scenarios: motion blur only, motion blur + noise  

- **Reproducible Pipeline**  
  - 60/20/20 train/val/test splits  
  - Standardized preprocessing (256×256 grayscale, normalization)  
  - Early stopping and checkpointing  



