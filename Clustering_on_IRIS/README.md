# CIFAR-100 Classification with Transfer Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/149-fnafykb9Y7V86NjeELow1Vs7CmDcm?usp=sharing)

This project demonstrates Transfer Learning for image classification on the CIFAR-100 dataset.  
It uses a pre-trained CNN backbone (such as ResNet or EfficientNet) for better accuracy and faster training.

---

## Workflow
1. Data Loading – Import CIFAR-100 dataset via Keras.  
2. Preprocessing – Normalize and resize images for pretrained models.  
3. Model Building – Use a pretrained backbone with custom classification layers.  
4. Training with Callbacks – Apply ModelCheckpoint and EarlyStopping.  
5. Fine-tuning – Unfreeze layers to boost performance.  
6. Evaluation – Test the final model and analyze results.  

---

## Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib  
