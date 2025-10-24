# ML_IA2 Poster presentation

# Malaria Detection Using Machine Learning and Deep Learning Approaches
---
## Group Number:6 
## Division : A
## Year : TY
---
## Group Members

**Yash Pathak**,
**Piyush Choudhury**,
**Soham Mishra**,
**Vedant Tendulkar**

---
## Overview

This repository presents a research poster summarizing and comparing four major academic studies focused on **automated malaria detection** using **machine learning (ML)** and **deep learning (DL)** techniques. The poster consolidates advancements in image analysis, convolutional neural networks (CNN), vision transformers (ViT), and hybrid diagnostic systems for malaria detection from microscopic blood smear images.

The goal of this work is to highlight state-of-the-art computational approaches that improve diagnostic accuracy, reduce dependence on manual microscopy, and enable deployment in resource-limited healthcare settings.

---

## Poster Title

**“Utilizing Image Analysis with Machine Learning and Deep Learning to Identify Malaria Parasites in Conventional Microscopic Blood Smear Images”**

View the full poster on Overleaf: [Click here to view](https://www.overleaf.com/read/tvbgxsjfprpc#6a9bcd)
View the full summary sheet on overleaf: [Click here to view] (https://www.overleaf.com/read/sfpnphgbjrmn#1f12ec)


---

## Research Papers Reviewed

### 1. *Utilizing Image Analysis with Machine Learning and Deep Learning to Identify Malaria Parasites in Conventional Microscopic Blood Smear Images*

**Authors:** Tamal Kumar Kundu, Dinesh Kumar Anguraj, Debnath Bhattacharyya
**Published in:** Traitement du Signal, Vol. 41, No. 1 (2024)
**Key Highlights:**

* Comprehensive review of image-based malaria detection using ML and DL.
* Comparison of techniques for **thin and thick blood smear** analysis.
* Explores image preprocessing, segmentation, feature extraction, and classification.
* Discusses the integration of **AI-driven microscopy** for low-resource regions.

---

### 2. *Enhancing Malaria Detection and Classification Using Convolutional Neural Networks–Vision Transformer Architecture*

**Authors:** Emmanuel Ahishakiye et al.
**Published in:** *Discover Applied Sciences* (2025)
**Key Highlights:**

* Proposes an ensemble model combining **CNN** and **Vision Transformer (ViT)**.
* Achieved **99.64% accuracy**, **99.23% precision**, and **99.75% recall**.
* Demonstrates robustness in both high-end and low-resource computational settings.
* Emphasizes **scalability, transfer learning**, and **global-feature modeling**.

---

### 3. *Deep Learning Based Automatic Malaria Parasite Detection from Blood Smear and Its Smartphone-Based Application*

**Authors:** K. M. Faizullah Fuhad et al.
**Published in:** *Diagnostics*, MDPI (2020)
**Key Highlights:**

* Introduces an efficient **CNN-based autoencoder model** with **99.23% accuracy**.
* Employs **knowledge distillation** and **data augmentation** to optimize training.
* Demonstrates practical deployment on **smartphones and web applications**, enabling sub-second inference time per sample.
* Focuses on **low-cost, real-time malaria screening** suitable for rural healthcare systems.

---
---
### 4. *Efficient Early Diagnosis of Malaria Using NASNet-Based Feature Extraction and Machine Learning Models*

**Authors:** Qadri et al.
**Published in:** *Sciencedirect*, SD(2023)
**Key Highlights:**

* Proposes a novel NASNet-Random Forest **(NNR)** approach for early malaria detection.
* Extracts spatial features from malaria cell images and generates class prediction probability features for training machine learning models.
* Achieves **99%** accuracy with an inference time of **~0.025** seconds per sample.
* Validated using k-fold cross-validation and optimized through hyperparameter tuning.
* Demonstrates potential for rapid, accurate malaria diagnosis to assist medical professionals in reducing mortality rates.
---
### 5. *Poster Compilation and Visualization (2025)*

**Authors:** Based on compiled works from the above studies
**Presented as:** A consolidated academic poster showcasing comparative insights into ML and DL approaches for malaria detection.
**Key Features:**

* Integrates data on feature extraction, classification accuracy, and computational efficiency.
* Visualized comparative results of CNN, ViT, and hybrid models.
* Designed for display in research symposia and data science conferences.

---

## Methodological Overview

| Technique                    | Description                                                               | Key Contribution                                       |
| ---------------------------- | ------------------------------------------------------------------------- | ------------------------------------------------------ |
| **Traditional ML**           | Uses feature extraction, morphological analysis, and SVM/KNN classifiers. | Established foundation for automated detection.        |
| **Deep CNN**                 | Learns spatial patterns in blood smear images.                            | High precision parasite classification.                |
| **Autoencoder-Based Models** | Compress and reconstruct cell features for improved inference speed.      | Reduced computational complexity.                      |
| **CNN-ViT Hybrid**           | Combines local and global feature modeling.                               | Superior accuracy and robustness across datasets.      |
| **Mobile AI Systems**        | Deploy lightweight models on smartphones.                                 | Enables accessible diagnosis in low-resource settings. |

---

## Technologies and Tools Used

* **Deep Learning Frameworks:** TensorFlow, Keras, PyTorch
* **Model Architectures:** CNN, Autoencoder, Vision Transformer (ViT), Ensemble Learning
* **Dataset:** NIH Malaria Cell Images Dataset (27,558 images)
* **Poster Design:** LaTeX BeamerPoster (A1 Landscape Layout)
* **Visualization:** Diagrams illustrating preprocessing, segmentation, and classification workflows

---
##Screenshot
<img width="1215" height="815" alt="image" src="https://github.com/user-attachments/assets/481ec32e-98c9-4a94-8862-30ad63789d52" />

---
## Repository Contents

```
├── README.md              # Documentation (this file)
├── out.pdf                # Poster (compiled A1 landscape)
├── s42452-025-06704-z.pdf # CNN-ViT Research Paper
├── diagnostics-10-00329-v2.pdf # CNN-Autoencoder Smartphone Paper
├── 1-s2.0-S2772662223001923-main #Transfer learning based paper
├── ML_Poster #Poster of the 4 research paper
├── Group_6_A.bib # Bib files
├── ML_IA2_Group_6_A #Summary sheet for the research papers
```

---


