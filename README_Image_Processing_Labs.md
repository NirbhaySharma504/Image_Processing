# Image Processing Laboratory Assignments

This repository contains my **Image Processing course lab assignments** implemented in Jupyter notebooks.  
Each notebook demonstrates a specific image processing concept, transformation, or model used during the course.

## About This Repository

These notebooks were created as part of my coursework to practice and understand fundamental and advanced image processing techniques.  
The assignments cover preprocessing, filtering, enhancement, thresholding, noise handling, feature extraction, and basic deep learning models used in image-related tasks.

## Contents

The repository includes the following notebooks:

- `Border on Input Image.ipynb`
- `CNN.ipynb`
- `Color to Grayscale.ipynb`
- `Confusion Matrix.ipynb`
- `Gray to Binary.ipynb`
- `Histogram Equalization.ipynb`
- `Image Compliment.ipynb`
- `Intensity Level Slicing.ipynb`
- `Log Transform.ipynb`
- `Power Law_ Gamma Transform.ipynb`
- `Adaptive Median Filter.ipynb`
- `Histogram Matching.ipynb`
- `Image Corrupted by Gaussian and Speckle Noise.ipynb`
- `Image Sharpening.ipynb`
- `Image Smoothing.ipynb`
- `Local Binary Pattern.ipynb`
- `Noise.ipynb`
- `Otsu_s Global Threshold.ipynb`
- `Pretained Model - VGG.ipynb`
- `Pretrained Models - Custom CNN, MobileNet, ResNet.ipynb`

## Topics Covered

The assignments explore a wide range of image processing concepts, including:

- image color space conversion
- binary thresholding
- histogram-based enhancement
- intensity transformations
- smoothing and sharpening
- noise addition and noise removal
- adaptive filtering
- texture and feature extraction
- classification using CNNs and pretrained models
- evaluation using confusion matrices

## Recommended Repository Structure

For GitHub, the cleanest way is to keep the notebooks in folders instead of putting everything flat in one directory.

A good structure would be:

```text
image-processing-labs/
├── README.md
├── notebooks/
│   ├── 01_color_to_grayscale/
│   │   └── Color to Grayscale.ipynb
│   ├── 02_gray_to_binary/
│   │   └── Gray to Binary.ipynb
│   ├── 03_histogram_equalization/
│   │   └── Histogram Equalization.ipynb
│   ├── 04_noise_and_filtering/
│   │   ├── Noise.ipynb
│   │   ├── Image Corrupted by Gaussian and Speckle Noise.ipynb
│   │   ├── Adaptive Median Filter.ipynb
│   │   ├── Image Smoothing.ipynb
│   │   └── Image Sharpening.ipynb
│   ├── 05_transformations/
│   │   ├── Log Transform.ipynb
│   │   ├── Power Law_ Gamma Transform.ipynb
│   │   ├── Intensity Level Slicing.ipynb
│   │   └── Image Compliment.ipynb
│   ├── 06_features_and_thresholding/
│   │   ├── Local Binary Pattern.ipynb
│   │   └── Otsu_s Global Threshold.ipynb
│   └── 07_deep_learning/
│       ├── CNN.ipynb
│       ├── Pretained Model - VGG.ipynb
│       └── Pretrained Models - Custom CNN, MobileNet, ResNet.ipynb
└── assets/
    └── sample_images/
```

## Why folders are better

Using folders makes the project easier to read and maintain because:

- notebooks are grouped by topic
- related images or datasets can be stored with the notebook
- the repo looks cleaner on GitHub
- it is easier for teachers or reviewers to find a specific assignment

If a notebook has its own input images or output figures, keep them inside the same assignment folder.

## How to Upload on GitHub

A simple workflow is:

1. Create one main repository for the course.
2. Add a `README.md` at the root.
3. Create topic-wise folders or assignment-wise folders.
4. Upload each notebook into the correct folder.
5. Add images, datasets, or output files only if they are small and necessary.
6. Ignore large generated files unless they are needed for evaluation.

## Notes

- If your notebooks contain results that depend on local paths, update them before uploading.
- Remove unnecessary large outputs if the notebook becomes too heavy.
- Make sure file names are clean and readable for GitHub.

## Suggested Short Description for GitHub

**Image Processing Lab Assignments completed as part of my course work, covering transformations, filtering, thresholding, noise handling, feature extraction, and deep learning-based image classification.**

## Author

**Hades**
