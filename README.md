
# Lightweight U-Net for Brain Tumor Segmentation  

![image](https://github.com/user-attachments/assets/419bd0dc-e9f8-4b6b-9d15-af6432bcc911)


This repository contains a **Jupyter Notebook** implementation of a **Lightweight U-Net model** for segmenting brain tumors using MRI images from the **BITE dataset**. The project leverages TensorFlow to modify the U-Net architecture for computational efficiency while maintaining accuracy.  

![image](https://github.com/user-attachments/assets/6295b797-6319-4ec8-9fc8-e7e985eaceac)

---

## 🧠 **Objective**  
The goal of this project is to propose a lightweight U-Net model to:  
1. Accurately segment brain tumors in pre- and post-operative MRI images.  
2. Visualize different slices of MRI images by manipulating the coordinates.  
3. Evaluate segmentation performance using key metrics like IoU and pixel accuracy.  

---

## 📂 **Repository Content**  
- **`brain-tumor-seg.ipynb`**: Contains the implementation, visualization, and evaluation of the Lightweight U-Net model.  

---
![image](https://github.com/user-attachments/assets/7d0e38a4-53a7-4742-9152-f3cff288639a)

## 🛠 **Key Features of the Model**  
- **Architecture**:  
  - Encoder: Compresses input images using convolutional layers and 2×2 max pooling.  
  - Decoder: Reconstructs images to original size using upsampling layers.  
  - 4 convolutional blocks, each with two 3×3 convolutional layers and zero padding.  
  - Filter sizes:  
    - **Encoder**: 128×128 → 64×64 → 32×32 → 16×16 → 8×8  
    - **Decoder**: 8×8 → 16×16 → 32×32 → 64×64 → 128×128  
- **Activation Function**: ReLU.  
- **Loss Function**: Binary Cross-Entropy.  
- **Optimizer**: Adam with a learning rate of 0.0001.  
- **Evaluation Metrics**:  
  - Pixel Accuracy.  
  - Mean Accuracy.  
  - Mean IoU.  
  - Frequency Weighted IoU (FWIoU).  

---

## 🚀 **How to Run**  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/VedantPancholi/Brain-Tumor-Segmentation.git  
   ```  

2. Open the Jupyter Notebook:  
   ```bash  
   jupyter notebook brain-tumor-seg.ipynb  
   ```  

3. Execute the notebook cells step-by-step to:  
   - Preprocess and visualize MRI images.  
   - Train the Lightweight U-Net model.  
   - Evaluate the model using IoU and pixel accuracy metrics.  

---

## 🎓 **Key Learnings**  
- Implemented a **lightweight U-Net architecture** optimized for brain tumor segmentation.  
- Enhanced understanding of **image segmentation** in the healthcare domain.  
- Gained hands-on experience with **TensorFlow**, **image processing**, and **evaluation metrics**.  
- Improved skills in visualizing and analyzing MRI images.  

---

## 📈 **Future Scope**  
- Optimize the model for deployment on edge devices.  
- Extend the methodology to other medical image segmentation tasks.  
- Integrate transfer learning techniques to enhance accuracy with limited data.  

---

## 🤝 **Collaborations & Opportunities**  
I am looking for opportunities in **Machine Learning** and **Data Science**, particularly in domains that require deep learning expertise for solving real-world problems.  

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/vedantpancholi/)   

---

This project reflects my passion for applying AI in healthcare and my commitment to developing impactful, innovative solutions.  

---  

Let me know if you’d like to refine it further! 😊
