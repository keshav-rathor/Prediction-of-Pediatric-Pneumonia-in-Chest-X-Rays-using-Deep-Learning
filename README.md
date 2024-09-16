# Pediatric Pneumonia Classification using Deep Learning

## Overview

This project aims to develop a deep learning model for classifying chest X-rays of pediatric patients to determine if they show signs of pneumonia. Leveraging transfer learning with a pre-trained DenseNet-161 model, this project focuses on fine-tuning the model to enhance its accuracy in detecting pneumonia from X-ray images.

## Project Details

The project involves:

1. **Data Acquisition**: Utilizing a dataset of labeled chest X-rays to train the model.
2. **Transfer Learning**: Employing DenseNet-161, a pre-trained convolutional neural network (CNN), and adapting it for pneumonia classification.
3. **Model Training**: Fine-tuning the DenseNet-161 model on the pediatric pneumonia dataset.
4. **Evaluation**: Assessing model performance using separate validation and testing datasets.
5. **Deployment**: Aiming for production deployment to assist in early diagnosis and treatment of pneumonia in pediatric patients.

## Dataset

The dataset used for this project is available on Kaggle:
- [Pediatric Pneumonia Chest X-ray Dataset](https://www.kaggle.com/datasets/andrewmvd/pediatric-pneumonia-chest-xray)

## Model Architecture

- **Pre-trained Model**: DenseNet-161
- **Network Type**: Convolutional Neural Network (CNN)
- **Adaptations**: Modified for pneumonia classification

## Installation

To get started, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/your-repository-name.git
cd your-repository-name
pip install -r requirements.txt
```

## Usage

1. **Prepare the Dataset**: Download the dataset from Kaggle and place it in the `data/` directory.
2. **Training**: Run the training script to fine-tune the DenseNet-161 model.

```bash
python train_model.py
```

3. **Evaluation**: Evaluate the model on validation and test sets.

```bash
python evaluate_model.py
```

4. **Deployment**: Instructions for deploying the model to a production environment will be provided in the `deployment/` directory.

## Results

The trained model will be evaluated based on metrics such as accuracy, precision, recall, and F1-score. Detailed results and performance metrics will be available in the `results/` directory.

