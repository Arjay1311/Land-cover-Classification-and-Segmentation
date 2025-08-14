# **Land Cover Classification & Segmentation**

**A deep learning-based system for classifying and segmenting land cover from high-resolution satellite imagery.**

---

## **Project Overview**
This project implements a **U-Net model** for **land cover classification** using high-resolution satellite images from the **Bhuvan dataset**.  
The system segments and classifies each pixel into one of **five land cover types**:

- **Vegetation**
- **Urban**
- **Forest**
- **Water**
- **Roads**

The model leverages **deep learning** and **image processing** techniques to enable **accurate semantic segmentation** for geospatial analysis.

---

## **Example Results**
**

---
## **Implementation Details**

### **1. Dataset**
- **Source:** **Bhuvan Dataset** (high-resolution satellite imagery)  
- **Preprocessing:** Normalization, resizing, and augmentation for improved training.

### **2. Model Architecture**
- **U-Net CNN** for pixel-level classification.  
- **Encoder-decoder** structure with skip connections for spatial detail preservation.

### **3. Training**
- **Loss Function:** Categorical Crossentropy  
- **Optimizer:** Adam  
- **Evaluation Metrics:** Accuracy, IoU (**Intersection over Union**)

### **4. Output**
- **Segmented map** highlighting vegetation, urban areas, forests, water bodies, and roads.

---


## **Tools & Technologies**
- **Language:** **Python**  
- **Libraries & Frameworks:**  
  - **TensorFlow / Keras** (U-Net implementation)  
  - **OpenCV** (image processing)  
  - **NumPy** & **Pandas** (data handling)  
  - **Matplotlib** (visualization)  
- **Concepts:**  
  - **Deep Learning** (CNNs)  
  - **Image Segmentation**  
  - **Computer Vision**

---

Deep Learning (CNNs)

Image Segmentation

Computer Vision
