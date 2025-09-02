# CIFAR-100 Classification with Checkpoints

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1VPv9g1men6XeL1zvTE_-wDdW4fPtMqxi?usp=sharing)

This project demonstrates training a **Convolutional Neural Network (CNN)** on the **CIFAR-100 dataset** using TensorFlow/Keras.  
It applies **data augmentation**, **regularization**, and **training callbacks** to build a robust image classifier.

---

## Workflow
1. **Data Loading** – Import CIFAR-100 dataset via Keras.  
2. **Preprocessing** – Normalize images and apply augmentation.  
3. **Model Building** – CNN with convolution, pooling, dropout, and batch normalization.  
4. **Training with Callbacks** – Use `ModelCheckpoint` and `EarlyStopping` to save the best model.  
5. **Evaluation** – Test the saved model and analyze accuracy.  
6. **Conclusion** – Suggestions for improvements and further experiments.

---

## Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib
