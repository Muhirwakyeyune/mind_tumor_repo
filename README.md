# Brain Tumor Classification using Deep CNN

## Abstract

Accurate classification of brain tumors is vital for precise medical interventions and patient care. This project explores the application of advanced deep learning architectures, including ResNet-50, EfficientNet, and DenseNet, for brain tumor classification using magnetic resonance imaging (MRI) scans. Leveraging the depth and skip connections of ResNet-50, the model automates the extraction of intricate features, enabling effective discernment of complex patterns indicative of various tumor types. Experimental results showcase the model's prowess in achieving remarkable precision, sensitivity, and specificity for different tumor classes. The utilization of ResNet-50 underscores its potential as a robust and efficient approach for precise brain tumor classification, contributing to heightened diagnostic accuracy and tailored medical strategies.

## Keywords
Brain Tumor Classification, Convolutional Neural Network (CNN), ResNet-50, MRI scans.

## Table of Contents
1. [Introduction](#1-introduction)
2. [Data Preparation](#2-data-preparation)
    1. [Image Dataset Summary](#21-image-dataset-summary)
3. [Methodology](#3-methodology)
    1. [Related Work](#31-related-work)
4. [Main Contribution](#4-main-contribution)
5. [Summary](#5-summary)
    1. [Conclusion](#51-conclusion)
6. [References](#6-references)

## 1. Introduction

This project focuses on brain tumor classification using the ResNet-50, EfficientNet, and DenseNet architectures, along with data augmentation techniques. The ResNet-50 model's depth and skip connections enable effective feature extraction, and data augmentation enhances model robustness. The objectives encompass implementing the pipeline, evaluating accuracy, and contributing to advancements in medical image analysis.

## 2. Data Preparation

The dataset comprises brain MRI scans from diverse sources. Preprocessing involves resizing and data augmentation techniques such as flipping and grayscale conversion. The dataset is split into training, validation, and test sets to ensure reliable evaluation. The brain tumor dataset introduced by Cheng et al. is utilized, containing 3064 MRI images of the brain, encompassing glioma, meningioma, and pituitary tumor categories.

### 2.1. Image Dataset Summary

| Class       | Glioma | Meningioma | No Tumor | Pituitary |
|-------------|--------|------------|----------|-----------|
| No. Images  | 1321   | 1339       | 1595     | 1457      |

## 3. Methodology

The ResNet-50, EfficientNet, and DenseNet architectures are selected for their proficiency in medical image analysis. Data augmentation techniques enhance model generalization, and class weights address class imbalance. The training strategy includes loss functions, optimizers, and learning rates.

### 3.1. Related Work

Building upon previous studies, this project focuses on ResNet-50, EfficientNet, and DenseNet architectures known for their feature extraction capabilities. Data augmentation and class weighting strategies are employed to improve model robustness.

## 4. Main Contribution

- Introduction of an enhanced model for improving brain tumor diagnosis.
- Proposal of a Brain Tumor Classification Model (BCM-CNN) based on advanced 3D models using ResNet-50, EfficientNet, and DenseNet architectures.
- The proposed BCM-CNN consists of two sub-modules: (i) CNN hyperparameter optimization using an Adam optimizer followed by model training, and (ii) Implementation of a segmentation model.

**Notebook Link:** [Kaggle](https://www.kaggle.com/code/muhirwasalomon/brain-tumor-classification-pytorch/edit/run/141279959)

## 5. Summary

Accurate brain tumor classification is essential for precision in medical interventions and patient care. This project leverages CNNs, including ResNet-50, EfficientNet, and DenseNet, to automate brain tumor classification from MRI scans. The comprehensive dataset and experimental results demonstrate remarkable precision, sensitivity, and specificity. ResNet-50 achieves 97.5/100 accuracy on validation, while EfficientNet achieves 98.5/100, and DenseNet achieves 98.4/100. This project contributes to improving diagnostic accuracy in medical image analysis.

### 5.1. Conclusion

Accurate brain tumor classification is essential for precision in medical interventions and patient care. Leveraging CNNs, including ResNet-50, EfficientNet, and DenseNet, this project achieves remarkable accuracy in brain tumor classification. The results underscore the potential of advanced architectures in enhancing diagnostic accuracy in medical image analysis.

## 6. References

1. Kaggle. Brain Tumor Classification in PyTorch. Available online: [Kaggle Brain Tumor Classification](https://www.kaggle.com/code/jarvisgroot/brain-tumor-classification-in-pytorch) (accessed on [access date]).

2. The Brain Tumour Charity. Brain Tumor Basics. Available online: [The Brain Tumour Charity](https://www.thebraintumourcharity.org/) (accessed on 1 July 2019).

3. American Cancer Society. Available online: [Cancer.org](https://www.cancer.org/cancer.html) (accessed on 1 July 2019).

4. Seetha, J., & S. S. Raja. "Brain Tumor Classification Using Convolutional Neural Networks." Biomedical Pharmacology Journal, Vol 11, pp 1457-1461, 2018. DOI: 10.1007/978-981-10-9035-6_33.

5. Bjoern H. Menze et al. "The Multi-modal Brain Tumor Image Segmentation Benchmark (BRATS)." IEEE Transactions on Medical Imaging.

6. Liu, J. et al. "A Survey of MRI-Based Brain Tumor Segmentation Methods." TSINGHUA Science and Technology, 2011;19;6.

7. Huda, S. et al. "A Hybrid Feature Selection with Ensemble Classification for Imbalanced Healthcare Data: A Case Study for Brain Tumor Diagnosis." IEEE Access, 2017;4.

8. Karuppathal and Palanisamy, V. "Fuzzy-based Automatic Detection and Classification." 
