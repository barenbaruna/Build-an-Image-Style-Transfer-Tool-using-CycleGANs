# Image Style Transfer Tool using CycleGANs

Transform your photos into Monet-esque paintings with this CycleGAN-based image style transfer tool!

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/74/Monet_dejeunersurlherbe.jpg/800px-Monet_dejeunersurlherbe.jpg" width="300"><br>
</div>

## Overview
Artists like Claude Monet are recognized for their unique styles, including color schemes and brush strokes. Replicating such styles manually is challenging even for professional painters. However, with the advent of Generative Adversarial Networks (GANs), particularly CycleGANs, Data Scientists and Machine Learning Engineers can develop models to transfer an artist's style to photographs.

This project guides you through building a style transfer tool using CycleGANs, enabling you to translate your photos into paintings reminiscent of Monet's style.

## Objectives
After completing this project, you will be able to:
- Understand the novelty of CycleGANs.
- Grasp the concept of Cycle Consistency Loss.
- Describe the complex architecture of CycleGANs.
- Learn best practices for training deep learning models.
- Implement a pre-trained CycleGAN for image style transfer.

## Setup
For this project, you will need the following libraries:
- <img src="https://www.cdnlogo.com/logos/n/81/numpy.svg" alt="Python" /> `numpy` for mathematical operations.
- <img src="https://cdn.jsdelivr.net/npm/programming-languages-logos/src/python/python_64x64.png" alt="Python" /> `Pillow` for image processing functions.
- <img src="https://cdn.jsdelivr.net/npm/programming-languages-logos/src/python/python_64x64.png" alt="Python" /> `tensorflow` for machine learning and neural network-related functions.
- <img src="https://cdn.jsdelivr.net/npm/programming-languages-logos/src/python/python_64x64.png" alt="Python" /> `matplotlib` for additional plotting tools.

## What is Image Style Transfer in Deep Learning?
## What is Image Style Transfer in Deep Learning?
Image Style Transfer involves translating one image into another while preserving its content but adopting the style of a reference image. For instance, transforming a photo into a painting resembling the style of Monet.

## CycleGANs
### Recap on Vanilla GANs
Vanilla GANs consist of a Generator network (G) and a Discriminator network (D). G generates fake images to fool D, while D distinguishes between real and fake images. Both networks improve iteratively through adversarial training.

### Novelty of CycleGANs
- Unlike traditional GAN models, CycleGANs don't require paired training data.
- CycleGANs utilize Cycle Consistency Loss to enforce forward-backward consistency of Generators.

### Forward-Backward Consistency
- CycleGANs ensure that translated images can be reverted to the original form.
- This is achieved by introducing an inverse mapping function, ensuring that G(F(y)) ≈ x and F(G(x)) ≈ y.

## Running the Project
1. Clone the repository: `https://github.com/barenbaruna/Build-an-Image-Style-Transfer-Tool-using-CycleGANs.git`
2. Navigate to the project directory: `cd Build-an-Image-Style-Transfer-Tool-using-CycleGANs`
3. Open the Jupyter Notebook: `jupyter notebook Build-an-Image-Style-Transfer-Tool-using-CycleGANs.ipynb`
4. Follow the instructions within the notebook to execute the project.

Enjoy transforming your photos into Monet-inspired paintings with ease!
