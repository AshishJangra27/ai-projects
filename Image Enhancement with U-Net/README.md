# Image Super-Resolution with U-Net

[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/ashishjangra27/face-resolution-enhancement-with-unet)  

---

This notebook demonstrates how to build and train a **U-Net model** for image super-resolution.  
The objective is to take a low-resolution image (64×64) and generate a high-resolution version (128×128).  

The U-Net architecture is well-suited for this task as it effectively captures both local and global features through its encoder-decoder structure with skip connections.

---

## Workflow
1. **Data Preparation** – Create low-resolution (64×64) and high-resolution (128×128) image pairs.  
2. **Model Building** – Implement the U-Net architecture with encoder-decoder blocks and skip connections.  
3. **Training** – Train the network to minimize reconstruction loss between generated and original high-res images.  
4. **Evaluation** – Compare outputs visually and with metrics (PSNR, SSIM).  

---

## Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib  
- OpenCV / PIL  


---

## References
- **U-Net Paper:** [Ronneberger et al. (2015)](https://arxiv.org/abs/1505.04597)  
- **Kaggle Notebook:** [Face Resolution Enhancement with U-Net](https://www.kaggle.com/code/ashishjangra27/face-resolution-enhancement-with-unet)  
