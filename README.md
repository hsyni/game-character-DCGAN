
# Game Character Generation using DCGAN and Transfer Learning

This repository contains the implementation code, dataset preparation scripts, and training procedures related to the following research study:

**"Generating a Realistic Game Character Face from a Single Portrait Using GANs"**

## Overview
This repository provides the source code and related materials for our study on generating realistic game character faces from single human portraits using Deep Convolutional Generative Adversarial Networks (DCGAN), enhanced by transfer learning and latent vector optimization.

## Contents

- **CharacterDCGAN.ipynb**: Notebook for training the DCGAN model from scratch.
- **PortraitToCharacterDCGAN.ipynb**: Notebook for applying latent vector optimization and transfer learning to generate personalized game characters from human portraits.

## Methodology

- **Data Preparation**: A dataset of 12,457 synthetic human portraits was stylized using AnimeGAN2.
- **Model Architecture**: DCGAN with Batch Normalization and transposed convolutions.
- **Transfer Learning**: Latent vector optimization using perceptual loss with a pre-trained VGG19 model.

## Results

The proposed model achieved a Fréchet Inception Distance (FID) score of **88.405**, demonstrating improved realism and stylistic coherence compared to existing methods.

## Dependencies
- Python 3.x
- TensorFlow
- OpenCV
- AnimeGAN2
- VGG19

## Citation
If you find this work useful, please cite:

```
Hüseyin Özgür Kazan, Dr. Osman Akın, "Generating a Realistic Game Character Face from a Single Portrait Using GANs"
```

## Contact
- **Corresponding author:** Hüseyin Özgür Kazan
- **Email:** huseyin.ozgur.kazan@gmail.com


