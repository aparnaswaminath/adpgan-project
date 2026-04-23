# ADP-GAN: Generative Modeling using GAN Architecture

## Overview
This project implements a Generative Adversarial Network (GAN) to learn complex data distributions and generate realistic synthetic samples. 
The model is built using a Generator–Discriminator framework where both networks compete and improve iteratively, resulting in high-quality generated outputs.
The adversarial training process enables the model to capture underlying data distributions effectively, making GANs powerful for data generation and augmentation tasks.

---

## Methodology
- Data preprocessing and normalization
- GAN architecture design (Generator & Discriminator)
- Adversarial training strategy
- Loss optimization and convergence monitoring

---

## Model Architecture
- Generator: Learns to create realistic data from noise
- Discriminator: Learns to distinguish real vs generated data
- Training: Alternating optimization between both networks

---

## Results
- Successful generation of synthetic samples
- Progressive improvement in output quality during training
- Stable adversarial learning observed after tuning

---

## Tech Stack
- Python
- NumPy
- PyTorch
- Matplotlib

--- 

## Future Work
- Improve training stability 
- Hyperparameter tuning
- Extend to domain-specific datasets
- Deploy as a generative service

---
## How to Run
```bash
# Clone the repository
git clone https://github.com/aparnaswaminath/adpgan-project.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook 
