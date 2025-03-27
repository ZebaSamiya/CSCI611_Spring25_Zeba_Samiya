# Quick Guide to Image Filtering & CNN Classification
### Overview
This repository contains two key scripts:
#####  Image Filtering with OpenCV – Applies edge detection, blurring, and scaling to an image.
#####  CNN-Based CIFAR-10 Classification – Trains a deep learning model to classify images.

## 1. Image Filtering Instructions
#### Setup
Install: Python 3.x, OpenCV, NumPy, Matplotlib, Seaborn.


Place an image (image.jpg) in the script directory.


#### Run & Output
- Converts image to grayscale.
- Applies edge detection (horizontal, vertical, diagonal).
- Performs blurring and scaling.
- Displays images and a bar chart of edge intensities.

## 2. CNN Classification Instructions
#### Setup
Install: Python 3.x, PyTorch, torchvision, NumPy, Matplotlib, Seaborn, Torchviz, Torchsummary.
####  Run & Output
- Loads CIFAR-10 dataset.
- Defines and trains a CNN model.
- Evaluates accuracy and loss.
- Generates:
  - CNN architecture visualization
  - Training accuracy/loss curves

## Expected Outputs
- Stylized image (structure from content + texture from style)
- Side-by-side comparison of content, style, and result
- Total, Content, and Style Loss plots

### Notes
- Feel free to swap in your own content/style images for experimentation.
- For best results, start from the content image (not noise).
- Use smaller image sizes for faster processing.
- Recommended: Run in Jupyter Notebook or Google Colab for better visualization.




