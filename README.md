# WRc Dataset Classification

This repository contains code and pre-trained models for deep learning-based sewer defect classification using the publicly available WRc sewer inspection dataset.

The models were obtained using the methods described in:

> A. George, W. Shepherd, S. Tait, L. Mihaylova, and S. Anderson, “A Deep Learning Benchmark Analysis of the Publicly Available WRc Dataset for Sewer Defect Classification” in *21st Computing & Control for the Water Industry Conference (CCWI)*, Sep. 2025, Sheffield, UK

We would appreciate it if you would cite this paper if you use this repository in your research.

---

## Important Notes on Model Weights and Data:

### Large Model Weights (Git LFS)

Due to their size, the pre-trained model weights (e.g., `.h5` files within `trainedWRc_resNet18_focalLoss.zip`) are stored using **Git Large File Storage (LFS)**.

**To properly download these large files, you *must* have Git LFS installed on your system and clone the repository using a Git client (like Git command line or GitKraken).**

If you download a ZIP file directly from GitHub's web interface, you will only receive small "pointer" files, not the actual model weights.

**Instructions for cloning with Git LFS:**

1.  **Install Git LFS:** If you don't have it, open your terminal/command prompt and run:
    ```bash
    git lfs install
    ```
    (You typically only need to do this once per machine.)
2.  **Clone the repository:**
    ```bash
    git clone https://github.com/alexgeorge13/WRc-Dataset-Classification.git
    ```

### Test Sample Image Origin

The `single_test_image.jpg` included in this repository is extracted from a real-world sewer pipe video dataset. This dataset was collected using a mobile CCTV inspection robot at the iCAIR facility, University of Sheffield.

> S. Edwards, R. Zhang, R. Worley, L. Mihaylova, J. Aitken, and S. R. Anderson, “A robust method for approximate visual robot localization in feature-sparse sewer pipes,” *Frontiers in Robotics and AI*, vol. 10, Mar. 2023.

---
