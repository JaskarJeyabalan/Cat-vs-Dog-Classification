# Cat vs Dog Image Classification System

An end-to-end Computer Vision project to classify images of cats and dogs using Deep Learning convolutional neural network (CNN) architectures.

---

## Project Overview

Image classification is a fundamental task in computer vision. This project builds a binary classification model designed to accurately distinguish between images of cats and dogs. It covers the full pipeline, including image preprocessing, data augmentation, custom CNN design, transfer learning with pre-trained models, hyperparameter tuning, and deployment readiness.

---

## Dataset Overview

The dataset contains labeled RGB images of cats and dogs organized into training and validation sets:

| Dataset | Split | Description |
| :--- | :--- | :--- |
| **Train Set** | ~80% | Labeled images of cats and dogs used for training model weights |
| **Validation Set** | ~20% | Independent set used to evaluate generalization performance during training |

---

## Technical Stack & Libraries

- **Language:** Python 3
- **Deep Learning Frameworks:** `tensorflow` / `keras` (or `torch`, `torchvision`)
- **Image Processing & Data Manipulation:** `opencv-python`, `Pillow`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Key Architectures:**
  - Custom Convolutional Neural Network (CNN)
  - Transfer Learning models (e.g., `MobileNetV2`, `ResNet50`, or `VGG16`)

---

## Project Structure

```text
.
├── Cat_vs_Dog_Classification.ipynb  # Main Jupyter notebook containing the full pipeline
└── README.md                        # Technical project documentation
