# Multiclass and Multilabel Classification with RoBERTa

## Description

### RoBERTa_Multiclass_Classification.ipynb
The project aims to implement a text classification model based on the RoBERTa architecture, adapted to handle multiple classes. It covers the entire process from data loading and preparation to training, evaluation, and model usage for predictions.

### RoBERTa_Multilabel_Classification.ipynb
This repository contains a Jupyter Notebook implementing a RoBERTa model for multilabel text classification, designed for tasks where each sample can belong to multiple labels simultaneously.

### Next Notebook

## Features
### RoBERTa_Multiclass_Classification.ipynb
- **RoBERTa Model**: Uses the RoBERTa architecture for text classification.
- **Multiclass**: Capable of classifying text into multiple categories.
- **Preprocessing**: Includes examples of text cleaning and preparation for NLP models.
- **Training and Evaluation**: Provides model training configuration and performance metrics.
- **GPU Support**: Configured to leverage GPU acceleration when available (e.g., A100 GPU).

### RoBERTa_Multilabel_Classification.ipynb
- End-to-end pipeline from data preprocessing to model evaluation
- Early stopping implementation to prevent overfitting
- Detailed performance metrics visualization
- GPU acceleration support
- Modular design for easy adaptation to custom datasets

## Notebook Structure 

### RoBERTa_Multiclass_Classification.ipynb
- **Data Loading**: Examples of loading and visualizing datasets.
- **Preprocessing**: Text cleaning and preparation for model input.
- **Model Definition**: Configuration and loading of the RoBERTa classification model.
- **Training**: Demonstrates the model training process, including train-validation splits.
- **Evaluation**: Computes performance metrics and analyzes results.
- **Predictions**: Uses the trained model for classifying new data.

### RoBERTa_Multilabel_Classification.ipynb
- **Data Loading**: Text cleaning and tokenization. Label processing for multilabel tasks. Train/validation split.
- **Model Configuration**: RoBERTa-base model with custom classification head. Multi-label compatible loss function (BCEWithLogitsLoss). AdamW optimizer with learning rate 2e-5
- **Training Process**: Batch training with progress tracking. Real-time loss/accuracy visualization. Early stopping with configurable patience. Model checkpointing
- **Evaluation & Metrics**: Accuracy and ROC-AUC scores. Classification report (precision/recall/F1). Prediction visualization

## Contributions

Contributions are welcome. If you wish to improve this project, please fork the repository and submit a pull request with your modifications.

## Contact

For questions or suggestions, contact me at [mabreucardenas95@gmail.com](mabreucardenas95@gmail.com).

