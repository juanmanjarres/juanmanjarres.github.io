---
title: AI + Astronomy
description: "Detecting 'invisible' comets with AI!"
summary: "How can we detect 'invisible' comets?"
cover:
  image: "projects/images/neuralnetwork.jpg"
---

## The Problem

Astronomical bodies can be hard to detect with our naked eye. Even with our most advanced tools, we are unable to recognize and detect certain bodies -- and more specifically, Category C comets. Thanks to the rise of Artificial Intelligence (AI), we can now use Convolutional Neural Networks (CNNs) to detect these comets.

## Detecting Comets with Convolutional Neural Networks (CNNs)

Convolutional Neural Networks (CNNs) are a class of deep learning algorithms that have proven to be highly effective in image recognition tasks. By training a CNN on a large dataset of astronomical images, it is possible to identify patterns and features that indicate the presence of comets. I focused on using CNNs to detect comets in astronomical images, particularly those that are faint or partially obscured, using publicly available datasets from NASA.

### Training the CNN

I trained the CNN on a dataset of astronomical images that contained both positive and negative examples of comets. Each set contained 5 images, which include the faint comets at times. The CNN was able to learn and recognize the pixel-sized differences on the images, and to distinguish the comets from other objects in the images. By using a large dataset and training the CNN on a powerful GPU, I was able to achieve high accuracy in detecting comets in the images.

### Technical Details

- **Language**: Python
- **Libraries**: TensorFlow, AstroML and Astropy (for astronomical data analysis)

### Results

I compared three various CNNs with different loss functions: Mean Squared Error (MSE), Mean Absolute Percentage Error (MAPE) and Mean Absolute Error (MAE). The CNN with the MAE loss function performed the best, achieving an accuracy of 75% in detecting comets in the images.

### Links

- [GitHub Repository](https://github.com/juanmanjarres/Astronomy)
- [Paper](/astronomy_paper.pdf)
