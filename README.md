# Adversarial Robustness of Kolmogorov–Arnold Networks (KANs)

This project explores the adversarial robustness of **Kolmogorov–Arnold Networks (KANs)** for image classification on the MNIST dataset. We compare KANs against standard neural network architectures (CNNs and MLPs) under common adversarial attack methods.

## 🧪 Objective

To evaluate whether KANs exhibit any intrinsic robustness to adversarial attacks like:

- **FGSM (Fast Gradient Sign Method)**
- **PGD (Projected Gradient Descent)**

## 🧠 Models

- **Kolmogorov–Arnold Networks (KAN)**
- **Convolutional Neural Networks (CNN)**
- **Multilayer Perceptrons (MLP)**
- **Combination of MLP and KAN layers**

## 🗂️ Dataset

- **MNIST**: Handwritten digit classification (28x28 grayscale images)

## 🔍 Findings

- All models were tested under FGSM and PGD attacks.
- No significant robustness differences were observed between KANs and baseline models (CNN/MLP).


<img width="1137" height="631" alt="kan" src="https://github.com/user-attachments/assets/7ac1d6b5-7a43-42df-bd22-e9e50a944861" />

