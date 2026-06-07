# Cardiovascular-heart-disease-detection

## Project Overview

Cardiovascular Disease (CVD) is one of the leading causes of mortality worldwide. Early and accurate detection is critical for improving patient outcomes and reducing healthcare costs. This project proposes a **multimodal deep learning and machine learning framework** that combines traditional cardiovascular risk-factor data with Electrocardiogram (ECG) images to improve the accuracy of cardiovascular disease detection.

The system leverages both numerical patient information and visual ECG patterns, enabling a more comprehensive analysis than single-source diagnostic approaches. By integrating multiple machine learning and deep learning models, the project aims to develop a robust and reliable cardiovascular disease prediction system.

---

## Objectives

* Develop an intelligent system for early cardiovascular disease detection.
* Integrate structured patient health data with ECG image analysis.
* Compare the performance of multiple machine learning and deep learning algorithms.
* Improve diagnostic accuracy through multimodal data fusion.
* Assist healthcare professionals in decision-making through AI-driven predictions.

---

## Problem Statement

Traditional cardiovascular disease detection methods often rely on either clinical data or ECG analysis independently. Such approaches may overlook important correlations between patient risk factors and cardiac electrical activity.

This project addresses these limitations by combining:

* Patient cardiovascular risk-factor data
* ECG image analysis
* Machine learning and deep learning techniques
* Ensemble-based prediction strategies

The integrated approach enables more accurate and reliable cardiovascular disease diagnosis.

---

## Key Features

### Structured Data Analysis

Analyzes patient health parameters such as:

* Age
* Gender
* Blood Pressure
* Cholesterol Levels
* Lifestyle Factors
* Medical History

### ECG Image Analysis

Processes ECG images to detect abnormal cardiac patterns using deep learning techniques.

### Machine Learning Models

Implemented algorithms include:

* Support Vector Machine (SVM)
* Random Forest
* XGBoost
* LightGBM
* CatBoost
* Recurrent Neural Network (RNN)
* Long Short-Term Memory (LSTM)

### Deep Learning for ECG Classification

* Convolutional Neural Networks (CNN)
* ROI-Based Feature Extraction
* CNN + Ensemble Classifiers

### Multimodal Fusion

Combines predictions from:

* Structured cardiovascular datasets
* ECG image datasets

to generate a more accurate final diagnosis.

---

## System Architecture

### Data Input

#### Dataset 1: Cardiovascular Disease Dataset

Contains patient health records and cardiovascular risk factors.

#### Dataset 2: ECG Image Dataset

Includes ECG images categorized into six classes:

* F
* M
* N
* Q
* S
* V

### Data Processing Pipeline

#### Structured Data Processing

* Missing value handling
* Data cleaning
* Feature scaling using Min-Max Normalization
* Outlier removal
* Train-test splitting

#### ECG Image Processing

* Image resizing
* Grayscale conversion
* Data augmentation
* Pixel normalization
* Label encoding

### Model Training

#### Structured Data Models

* SVM
* Random Forest
* XGBoost
* LightGBM
* CatBoost
* LSTM
* RNN

#### ECG Models

* CNN
* CNN + Random Forest
* CNN + MLP
* Gradient Boosting Models

### Prediction Fusion

Outputs from both modalities are combined to improve overall cardiovascular disease detection performance.

---

## Technologies Used

| Category             | Technologies        |
| -------------------- | ------------------- |
| Programming Language | Python              |
| Data Processing      | Pandas, NumPy       |
| Machine Learning     | Scikit-Learn        |
| Deep Learning        | TensorFlow, Keras   |
| Image Processing     | OpenCV              |
| Visualization        | Matplotlib, Seaborn |
| Notebook Environment | Jupyter Notebook    |

---

## Project Structure

```text
Cardiovascular-Disease-Detection/
│
├── Cardiovascular_Disease_Dataset.csv
├── NITTTR_CARDIOVASCULAR_ECG.ipynb
├── README.md
│
├── ECG_Image_Data/
│   ├── F/
│   ├── M/
│   ├── N/
│   ├── Q/
│   ├── S/
│   └── V/
│
├── outputs/
│   ├── model_results/
│   ├── confusion_matrices/
│   └── prediction_graphs/
│
└── report/
    └── Cardiovascular_Detection_Report.pdf
```

---

## Methodology

### Step 1: Data Preprocessing

* Missing value treatment
* Feature scaling
* Data normalization
* Outlier removal

### Step 2: ECG Image Processing

* Grayscale conversion
* Resizing
* Data augmentation
* Feature extraction

### Step 3: Model Training

Train multiple machine learning and deep learning models on both datasets.

### Step 4: Multimodal Fusion

Combine predictions from structured and image-based models.

### Step 5: Evaluation

Evaluate performance using:

* Accuracy
* Precision
* Recall
* F1-Score

---

## Results

The study demonstrated that:

* Individual machine learning models achieved strong performance on structured cardiovascular data.
* CNN-based models successfully classified ECG images.
* The multimodal fusion model outperformed individual approaches.
* Combining numerical patient data and ECG images improved prediction accuracy and reliability.

---

## Future Enhancements

* Real-time ECG monitoring integration
* Mobile healthcare application deployment
* Explainable AI for clinical decision support
* Integration with wearable health devices
* Cloud-based disease prediction platform

---

## Applications

* Clinical Decision Support Systems
* Smart Healthcare Platforms
* Remote Patient Monitoring
* Preventive Cardiology
* AI-Assisted Diagnosis

---

## Conclusion

This project demonstrates the effectiveness of a multimodal approach for cardiovascular disease detection by combining structured patient data and ECG image analysis. The integrated framework provides higher predictive accuracy than standalone methods and highlights the potential of artificial intelligence in advancing cardiovascular healthcare and early disease diagnosis.
