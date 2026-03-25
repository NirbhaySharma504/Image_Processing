# Image Processing Lab Assignments

This repository contains my **Image Processing course laboratory assignments**, completed as part of my academic coursework and prepared for evaluation and portfolio use.

The notebooks document a progression of classic image processing techniques and introductory deep learning experiments that build a strong foundation in **computer vision**, **visual computing**, and related interactive/immersive applications.

## About the Project

Image processing forms the core of many modern visual systems, from object understanding and scene enhancement to real-time perception pipelines used in computer vision and VR-oriented applications.  
This repository brings together my lab work on transformations, filtering, histogram-based enhancement, thresholding, noise handling, feature extraction, and pretrained neural network models.

The goal of these assignments is to demonstrate practical understanding of:
- image representation and manipulation
- enhancement and restoration
- binary and adaptive thresholding
- noise generation and filtering
- texture and feature extraction
- classification with CNNs and pretrained models
- evaluation using confusion matrices

## Repository Structure

The notebooks are organized in topic-wise folders for clarity and easy review:

```text
Image-Processing-Labs/
├── README.md
├── notebooks/
│   ├── 01_color_conversion/
│   │   └── Color to Grayscale.ipynb
│   ├── 02_binary_thresholding/
│   │   └── Gray to Binary.ipynb
│   ├── 03_histogram_processing/
│   │   ├── Histogram Equalization.ipynb
│   │   └── Histogram Matching.ipynb
│   ├── 04_intensity_transformations/
│   │   ├── Log Transform.ipynb
│   │   ├── Power Law_ Gamma Transform.ipynb
│   │   ├── Intensity Level Slicing.ipynb
│   │   └── Image Compliment.ipynb
│   ├── 05_noise_and_filtering/
│   │   ├── Noise.ipynb
│   │   ├── Image Corrupted by Gaussian and Speckle Noise.ipynb
│   │   ├── Adaptive Median Filter.ipynb
│   │   ├── Image Smoothing.ipynb
│   │   └── Image Sharpening.ipynb
│   ├── 06_features_and_thresholding/
│   │   ├── Local Binary Pattern.ipynb
│   │   └── Otsu_s Global Threshold.ipynb
│   ├── 07_basics_and_evaluation/
│   │   ├── Border on Input Image.ipynb
│   │   └── Confusion Matrix.ipynb
│   └── 08_deep_learning/
│       ├── CNN.ipynb
│       ├── Pretrained Model - VGG.ipynb
│       └── Pretrained Models - Custom CNN, MobileNet, ResNet.ipynb
└── assets/
    └── sample_images/
```

## Notebook List

The repository includes the following lab notebooks:

- `Border on Input Image.ipynb`
- `CNN.ipynb`
- `Color to Grayscale.ipynb`
- `Confusion Matrix.ipynb`
- `Gray to Binary.ipynb`
- `Histogram Equalization.ipynb`
- `Histogram Matching.ipynb`
- `Image Compliment.ipynb`
- `Intensity Level Slicing.ipynb`
- `Log Transform.ipynb`
- `Power Law_ Gamma Transform.ipynb`
- `Adaptive Median Filter.ipynb`
- `Image Corrupted by Gaussian and Speckle Noise.ipynb`
- `Image Sharpening.ipynb`
- `Image Smoothing.ipynb`
- `Local Binary Pattern.ipynb`
- `Noise.ipynb`
- `Otsu_s Global Threshold.ipynb`
- `Pretained Model - VGG.ipynb`
- `Pretrained Models - Custom CNN, MobileNet, ResNet.ipynb`

## Topics Covered

### Image Enhancement and Transformation
- grayscale conversion
- complement operation
- logarithmic transformation
- gamma correction
- intensity slicing
- histogram equalization and matching

### Noise and Restoration
- Gaussian noise
- speckle noise
- image smoothing
- sharpening
- adaptive median filtering

### Segmentation and Thresholding
- global thresholding
- Otsu’s method
- binary image generation

### Feature Extraction and Analysis
- local binary patterns
- border and edge-related operations
- confusion matrix interpretation

### Deep Learning
- custom CNN implementation
- pretrained VGG-based classification
- comparison of pretrained and custom architectures
- evaluation of model performance

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- OpenCV
- Matplotlib
- scikit-image
- scikit-learn
- TensorFlow / Keras or PyTorch, depending on the notebook implementation

## How to Run

1. Clone the repository.
2. Open the required notebook in Jupyter Notebook or JupyterLab.
3. Run the cells in order.
4. Make sure the required libraries are installed in your environment.

Example installation:

```bash
pip install numpy opencv-python matplotlib scikit-image scikit-learn jupyter
```

If any notebook uses a deep learning framework, install the required backend as well:

```bash
pip install torch torchvision
```

or

```bash
pip install tensorflow
```

depending on the notebook.

## Notes for Review

- These notebooks were prepared as part of my course laboratory work.
- The repository is organized to make each assignment easy to navigate.
- The content reflects practical implementation of core image processing concepts and early-stage visual learning workflows.

## Why This Repository Matters

This project shows my hands-on experience with the building blocks that support modern visual systems.  
The assignments strengthen the fundamentals needed for computer vision tasks such as preprocessing, feature extraction, classification, and image enhancement, which are also relevant to immersive and VR-related visual pipelines.

## Author

**Nirbhay**
