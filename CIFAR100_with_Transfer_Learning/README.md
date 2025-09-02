# CIFAR-100 Classification with Transfer Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1i9DMRkn_lrNHq1rUphKIkhSTBlvhVBo_?usp=sharing)

This project demonstrates **Transfer Learning** for image classification on the **CIFAR-100 dataset**.  
It leverages a **pre-trained CNN backbone** (e.g., ResNet, EfficientNet) for faster convergence and improved performance.

---

## Workflow
1. **Data Loading** – Import CIFAR-100 dataset via Keras.  
2. **Preprocessing** – Normalize and resize images for pretrained models.  
3. **Model Building** – Use a pretrained backbone with custom classification layers.  
4. **Training with Callbacks** – Use `ModelCheckpoint` and `EarlyStopping`.  
5. **Fine-tuning** – Unfreeze layers to boost accuracy.  
6. **Evaluation** – Test the final model and analyze results.  

---

## Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib  
