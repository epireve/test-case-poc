# ML Model Benchmarking for Text Classification

## Overview
This project benchmarks different ML algorithms for text classification tasks. It compares the performance of various popular classifiers to help determine the most effective approach for text classification.

## Algorithms Compared
- Multinomial Naïve Bayes
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Logistic Regression

## Performance Metrics
Each algorithm is evaluated based on:
- Accuracy
- Training Time
- Cross-validation Scores
- Confusion Matrix

## Key Features
- Uses scikit-learn pipelines for consistent preprocessing
- Implements TF-IDF vectorization for text features
- Provides visual comparisons of model performance
- Uses Pydantic for type safety and data validation
- Includes comprehensive error analysis

## Results Summary
Based on the benchmark results:
- SVM achieved the highest accuracy (92.33%)
- Decision Tree showed strong performance (92.22%)
- Random Forest performed well (90.44%)
- Logistic Regression achieved 86.67%
- Multinomial NB reached 80.00%

## Usage
1. Ensure you have the required dependencies installed
2. Place your labeled text data in CSV format
3. Run the benchmark notebook
4. View the comparative results and visualizations

## Project Structure 
├── README.md
├── benchmark.ipynb
└── test-demo.ipynb

## Future Improvements
- Add more algorithms for comparison
- Implement hyperparameter tuning
- Add more evaluation metrics
- Support for multilabel classification
- Cross-validation with different data splits
