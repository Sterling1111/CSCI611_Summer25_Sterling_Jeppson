# Assignment 3 - Style Transfer with Deep Neural Networks

This assignment implements neural style transfer using a pre-trained VGG19 network, following the method outlined in "Image Style Transfer Using Convolutional Neural Networks" by Gatys et al.

## Requirements

- Python 3.13.5
- PyTorch
- torchvision
- matplotlib
- PIL (Pillow)
- numpy

## Setup

1. Install required dependencies:
```bash
pip install torch torchvision matplotlib pillow numpy
```

2. Ensure you have the sample images in the Assignment_3 directory:
   - `sterling.jpg` (content image)
   - `the-old-guitarist.jpg` (style image)
   - Additional style images: `house.jpg`, `miyazaki.jpg`, `red.jpg`, `starry.jpg`

## Running the Code

1. Open the Jupyter notebook:
```bash
jupyter notebook Style_Transfer_Exercise.ipynb
```

2. Run all cells in sequence to:
   - Load and preprocess content and style images
   - Extract features using pre-trained VGG19
   - Perform iterative style transfer optimization
   - Display the final stylized image

## Notes

- The notebook uses a pre-trained VGG19 model for feature extraction
- Style transfer is performed through gradient descent optimization
- You can experiment with different content and style images by modifying the image file paths in the notebook
- Adjust the `steps` parameter (default: 2000) and learning rate for different results