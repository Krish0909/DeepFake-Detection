# DeepFake Detection

This repository contains a deep learning model for detecting DeepFake images using PyTorch and the EfficientNet-B0 architecture. The model is trained on a dataset of real and DeepFake images, and it can classify new images as either "real" or "fake."

## Project Setup

### Prerequisites

- Python 3.x
- PyTorch
- torchvision
- Kagglehub (for dataset download)
- Google Colab (for training and saving the model)

### Dataset

The dataset used for this project is the [DeepFake and Real Images dataset](https://www.kaggle.com/datasets/manjilkarki/deepfake-and-real-images), which is automatically downloaded from Kaggle using the `kagglehub` library.

### Dependencies

Install the required libraries using `pip`:

```bash
pip install torch torchvision kagglehub
