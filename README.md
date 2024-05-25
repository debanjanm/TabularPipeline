# TabularPipeline

## Overview
TabularPipeline is a robust and efficient pipeline designed for handling tabular data. It streamlines the processes of data preprocessing, feature engineering, model training, and evaluation, making it ideal for data science projects involving structured datasets.

## Features
- Data cleaning and preprocessing
- Feature engineering
- Model training and tuning
- Model evaluation and validation
- Saving and loading models

## Installation
```bash
pip install tabularpipeline

Usage
Example Workflow

from tabularpipeline import TabularPipeline

# Initialize the pipeline
pipeline = TabularPipeline(config_path='config.yaml')

# Load data
pipeline.load_data('data/raw/dataset.csv')

# Preprocess data
pipeline.preprocess()

# Perform feature engineering
pipeline.feature_engineering()

# Train model
pipeline.train_model()

# Evaluate model
pipeline.evaluate_model()

# Save the trained model
pipeline.save_model('models/trained_model.pkl')

