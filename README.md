# GenerativeAI-Image-Synthesis

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.x-red?style=flat-square&logo=pytorch)](https://pytorch.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=flat-square&logo=tensorflow)](https://www.tensorflow.org/)

A project exploring various techniques for generative AI, specifically focusing on image synthesis. This repository provides implementations of popular generative models such as Generative Adversarial Networks (GANs), Variational Autoencoders (VAEs), and Diffusion Models. The goal is to understand the underlying principles and practical applications of these models in generating realistic and novel images.

## 🌟 Features

- **GAN Implementations:** Deep Convolutional GAN (DCGAN), Conditional GAN (cGAN), and StyleGAN (simplified).
- **VAE Implementations:** Standard Variational Autoencoder for image generation.
- **Diffusion Models:** Basic implementation of a Denoising Diffusion Probabilistic Model (DDPM).
- **Dataset Integration:** Examples using datasets like MNIST, CIFAR-10, and CelebA.
- **Training and Generation Scripts:** Scripts for training models and generating new images.
- **Evaluation Metrics:** Tools for evaluating generated image quality (e.g., FID, Inception Score).

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- pip

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/Enten1992/GenerativeAI-Image-Synthesis.git
    cd GenerativeAI-Image-Synthesis
    ```
2.  Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
3.  Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## 📂 Project Structure

```
GenerativeAI-Image-Synthesis/
├── models/
│   ├── gan/
│   │   ├── dcgan.py
│   │   └── cgan.py
│   ├── vae/
│   │   └── vae.py
│   └── diffusion/
│       └── ddpm.py
├── data/
├── scripts/
│   ├── train_gan.py
│   └── generate_images.py
├── utils/
├── requirements.txt
├── LICENSE
└── README.md
```

## 📈 Usage

### 1. Train a DCGAN on MNIST

```bash
python scripts/train_gan.py --model dcgan --dataset mnist --epochs 50
```

### 2. Generate Images

```bash
python scripts/generate_images.py --model dcgan --num_images 16 --output_dir generated_images
```

## 🤝 Contributing

Contributions are welcome! Please feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

Ethan Reed - ethan.reed.ai@example.com

Project Link: [https://github.com/Enten1992/GenerativeAI-Image-Synthesis](https://github.com/Enten1992/GenerativeAI-Image-Synthesis)
