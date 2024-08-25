# ECG Classification based on Time Frequency Analysis and Deep Learning

## Project Overview

This project aims to classify human electrocardiogram (ECG) signals into three categories: Cardiac Arrhythmia (ARR), Congestive Heart Failure (CHF), and Normal Sinus Rhythm (NSR). By utilizing time-frequency representations of ECG signals and applying deep convolutional neural networks (CNNs), this project seeks to improve the accuracy and efficiency of diagnosing heart conditions.

## Objectives

- **Develop an effective model** for classifying ECG signals into ARR, CHF, and NSR.
- **Utilize time-frequency analysis** to convert ECG signals into time-frequency images, capturing both temporal and spectral information.
- **Leverage deep learning models**, particularly CNNs, to process these images and achieve high classification accuracy.

## Motivation and Relevance

The project supports **Sustainable Development Goal 3 (Good Health and Well-being)** by improving the diagnostic processes for cardiovascular diseases. With cardiovascular diseases being a leading cause of mortality worldwide, enhancing the accuracy and efficiency of ECG classification directly contributes to better health outcomes.

## Dataset

- **Source**: PhysioNet databases, including the MIT-BIH Arrhythmia Database, MIT-BIH Normal Sinus Rhythm Database.
- **Format**: The ECG recordings are in MATLAB format (`.mat`), with each signal sampled at 128 Hz.
- **Size**: The dataset includes 162 recordings, consisting of 96 ARR, 30 CHF, and 36 NSR recordings.

## Methodology

### 1. Data Preprocessing
- Convert the ECG signals into time-frequency images using techniques like wavelet transform.
- Save the time-frequency representations as RGB images for input into CNNs.

### 2. Model Development
- Implement deep convolutional neural networks (CNNs) to classify the time-frequency images.
- Explore transfer learning techniques by fine-tuning pretrained CNN models like GoogLeNet for ECG classification.

### 3. Evaluation
- Assess model performance using metrics like accuracy, precision, recall, and F1-score.
- Compare the effectiveness of different time-frequency analysis methods and CNN architectures.

## Results

The project's anticipated outcomes include:
- Improved classification accuracy for ECG signals using deep learning models.
- Demonstrated effectiveness of time-frequency analysis in biomedical signal processing.
- Insights into the use of transfer learning in medical image classification.

## Project Structure

```bash
├── data/               # Directory containing the dataset
├── models/             # Directory containing trained models
├── notebooks/          # Jupyter notebooks for experiments and analysis
├── scripts/            # Python/Matlab scripts for data preprocessing and model training
├── results/            # Directory for storing model results and evaluation metrics
├── README.md           # Project overview and setup instructions
└── requirements.txt    # Dependencies for the project
