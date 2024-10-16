# Palmprint Recognition Based on Siamese Networks

This repository contains the implementation of a palmprint recognition system using Siamese Networks. The model is trained and tested on the [Tongji Contactless Palmprint Database](https://cslinzhang.github.io/ContactlessPalm/), a publicly available dataset of contactless palm images.

## Dataset

We utilize the [Tongji Contactless Palmprint Database](https://cslinzhang.github.io/ContactlessPalm/) for training and evaluating our model. This dataset provides a wide range of contactless palm images, making it ideal for developing robust palmprint recognition systems.

## ROI Extraction

For the Region of Interest (ROI) extraction, we adopt the methodology from the following work:

```bibtex
@misc{holzweberPalm2022,
  author = {Christopher Holzweber},
  title = {Palmprint Recognition with Neural Networks},
  year = {2022},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/holzweber/palmprint-recognition/}}
}
```

The ROI extraction process is crucial for accurately isolating the palm region, which enhances the performance of the Siamese Network by focusing on the most relevant features of the palmprint.

## Model Overview
The core of this project is a Siamese Network, a type of neural network architecture designed to find the similarity between two inputs. This architecture is particularly well-suited for tasks like palmprint recognition, where the goal is to determine whether two palm images belong to the same individual.

## Authentication App
<img width="772" alt="image" src="https://github.com/user-attachments/assets/8368dcc2-64d4-439d-b857-77c2ce04fbe7">


