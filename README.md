# 🤖🔢 MNIST GAN Project

![GAN](https://img.shields.io/badge/GAN-Generative%20Adversarial%20Network-blue)
![Python](https://img.shields.io/badge/Python-3.8%2B-green)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)


## 📝 About the Project

This project demonstrates the implementation of GAN (Generative Adversarial Network) on the MNIST handwritten digits dataset, showcasing a significant model in the field of artificial intelligence and deep learning.

### 🎯 Project Objectives
- Generate realistic handwritten digit images
- Demonstrate GAN model principles through practical implementation
- Visualize the training process of deep learning models
## ✨ Features

- 🔄 MNIST dataset integration
- 🏗️ Implementation of Generator and Discriminator models
- 📊 Visualization tools
- 📈 Real-time training process monitoring
- 🖼️ Generated image visualization
- 🎨 Customizable model parameters

## 🛠️ Requirements

🐍 python

🐼 pandas==1.5.3

📊 numpy==1.23.5

📈 matplotlib==3.7.1

🌈 seaborn==0.12.2

🤖 tensorflow==2.12.0

100% ██████ tqdm==4.65.0

## 🏗️ Model Architecture

### 🔧 Generator
- **Input**: 100-dimensional noise vector
- **Output**: 28x28x1 image
- **Layers**:
  - Dense (6272 neurons)
  - LeakyReLU activation function
  - Reshape (7x7x128)
  - BatchNormalization
  - Conv2DTranspose layers

### 🔍 Discriminator
- **Input**: 28x28x1 image
- **Output**: 1 (real/fake classification)
- **Layers**:
  - Conv2D layers
  - LeakyReLU activation function
  - Dropout (0.3)
  - Dense
 
## ⚙️ Training Parameters

| Parameter | Value |
|-----------|--------|
| Number of Epochs | 10000 |
| Batch Size | 64 |
| Learning Rate | 0.0002 |
| Optimizer | Adam (beta1=0.5) |
| Latent Dimension | 100 |

## 📊 Results

After model training:
- Generated sample images
- Training loss values
- Discriminator and Generator performance graphs

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔍 Code And Kaggle Link
Project: [gan-mnist.ipynb](https://github.com/omerfarukyuce/GAN-MNIST/blob/main/gan-mnist.ipynb)

Kaggle: [🤖🔢GAN MNIST](https://www.kaggle.com/code/merfarukyce/gan-mnist)
