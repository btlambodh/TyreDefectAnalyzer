# TyreDefectAnalyzer - Tyre Defect Classification Project

This repository contains the implementation of a **Tyre Defect Classification System**, focusing on distinguishing between **Good** and **Defective** tyres. The project includes Exploratory Data Analysis (EDA), implementation of Convolutional Neural Networks (CNNs), hyperparameter tuning using Optuna, and evaluations using various pre-trained models such as ResNet50, EfficientNetB0, and DenseNet121.

---

## Features

- **Dataset Preparation**: Clean dataset splitting into training, validation, and test sets with an organized directory structure.
- **Exploratory Data Analysis (EDA)**: Visualizations and statistical insights into the dataset to identify trends and preprocessing needs.
- **Custom CNN Model**: Implementation of a foundational CNN for binary classification.
- **Hyperparameter Tuning**: Utilized **Optuna** to optimize hyperparameters and improve CNN performance.
- **Pre-Trained Models**: Leveraged state-of-the-art architectures such as ResNet50, EfficientNetB0, and DenseNet121 for enhanced performance.
- **Visualization**: Heatmaps, classification reports, and training metrics for model evaluation.

---


## Future Enhancements

- **Grad-CAM Visualization**:
  - Implement Grad-CAM to highlight defective regions in tyre images.
- **Object Detection**:
  - Extend the model to identify specific defective portions using bounding boxes.
- **Data Augmentation**:
  - Include more diverse augmentations to enhance generalization.
- **Model Deployment**:
  - Deploy the model as a web application using Streamlit or Flask for real-time classification.
- **Integration with IoT**:
  - Embed the model into edge devices for live defect detection during tyre manufacturing.

---

