# CIFAR-100 Classification with Checkpoints

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/16hORasD-xxWQARfA-htxOlsivFRDRHgG?usp=sharing)

**Overview:** Train a CNN on the CIFAR-100 dataset using TensorFlow/Keras with data augmentation, regularization, and training callbacks to build a robust image classifier.

## Workflow
1. **Data Loading** — Load CIFAR-100 via Keras.
2. **Preprocessing** — Normalize images; apply augmentation (flips/shifts/rotations).
3. **Model Building** — Convolution + pooling blocks, Batch Normalization, Dropout.
4. **Training with Callbacks** — Use `ModelCheckpoint` and `EarlyStopping`; monitor validation metrics.
5. **Evaluation** — Reload best checkpoint; report test accuracy; analyze misclassifications.
6. **Conclusion** — Suggest stronger backbones (e.g., ResNet/EfficientNet), tune augmentation/regularization, add LR scheduling & mixed precision, and run class-wise metrics/confusion matrix.

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib


Vizlearn: https://vizlearn.in/

CNN Visualizer: https://adamharley.com/nn_vis/cnn/3d.html

MNIST with ANN: https://gemini.google.com/share/a3e2aa44acee

CIFAR10 with ANN: https://gemini.google.com/share/39228ae8a1e8

MNIST with CNN: https://gemini.google.com/share/5756846e360c
