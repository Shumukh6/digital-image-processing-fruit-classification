# Advanced Digital Image Processing (DIP) Project

This project was developed for the AI342 course (Advanced Digital Image Processing) at Taibah University.

## Project Overview
This project focuses on applying digital image processing techniques for image restoration, enhancement, segmentation, morphology, and classification.

We used fruit images (mainly apples and bananas) to analyze different image processing methods and evaluate their performance in handling noise and extracting useful features.

## Objectives
- Add and analyze different types of noise in images
- Restore noisy images using suitable filters
- Apply enhancement techniques to improve image quality
- Perform image segmentation and morphology operations
- Extract image features for classification

## Techniques Used
### Noise Types
- Salt & Pepper Noise
- Gaussian Noise
- Periodic Noise
- Rayleigh Noise
- Uniform Noise

### Filters & Transformations
- Median Filter
- Mean Filter
- Low Pass Filter
- Notch Filter
- Laplacian Filter
- Gamma Transformation
- Log Transformation

### Segmentation & Morphology
- Global Thresholding
- Adaptive Thresholding
- Otsu Thresholding
- Erosion
- Dilation
- Opening
- Closing
- Boundary Extraction

## Feature Extraction
The following features were extracted for classification:
- Area
- Perimeter
- Circularity
- Compactness
- Hu Moments
- Solidity

## Classification
Initially, the dataset was classified into:
- Apple
- Banana

Later, a third class was added:
- Apple with Leaf

This improved classification performance because leaf presence affected shape-based features.

## Evaluation Metrics
We evaluated restoration quality using:
- **PSNR (Peak Signal-to-Noise Ratio)** → Higher is better
- **MSE (Mean Squared Error)** → Lower is better

## Tools & Libraries
- Python
- NumPy
- OpenCV
- scikit-image
- Matplotlib
- Jupyter Notebook

## Dataset
A subset of a Kaggle fruit dataset was used, containing images of:
- Apples
- Bananas

## Team Members
- Bushra Abdulrahman Almutrafi
- Razan Hamdan Almuzaini
- Shatha Ibrahim Ghabban
- Shumukh Eid Alotaibi
- Layal Mohammed Alhazmi
- Hatoon Mohammed Ghabban
