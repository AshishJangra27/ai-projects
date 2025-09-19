# Gender Style Transfer


[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/ashishjangra27/gender-style-transfer)  

---

This repository contains the code to perform **gender-specific style transfer** on images.  
It combines a gender classification model with style transfer techniques and GAN-based face generation to create realistic gender-conditioned outputs.

---

## Workflow
1. Gender Classification – Use a pre-trained MobileNet classifier to detect gender from images.  
2. Style Transfer – Apply gender-specific styles using neural style transfer methods.  
3. Face Generation – Train a GAN model to generate realistic human faces.  
4. Integration – Combine classification, generation, and style transfer for final outputs.  

---

## Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib  
- GANs (Generator + Discriminator)  

---

## References
- **Classifier Model:** [Gender Classifier - MobileNet](https://www.kaggle.com/models/ashishjangra27/gender-classifier-mobilenet/)  
- **Style Transfer Notebook:** [Gender Style Transfer](https://www.kaggle.com/code/ashishjangra27/gender-style-transfer)  
- **GAN Model Training Notebook:** [Face Generation with GAN](https://www.kaggle.com/code/ashishjangra27/face-generation-with-gan)  
- **Generator Model:** [Face Generator with GAN - GitHub](https://github.com/AshishJangra27/ai-projects/blob/main/Face%20Generator%20with%20GAN/generator_700.h5)  
