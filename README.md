# ML Classification with Hyperparameter Tuning and Fairness Analysis
Built and optimized a neural network classifier through systematic experimentation (architectures, optimizers, batch sizes), achieving 85.67% accuracy while analysing performance gaps across demographic groups to evaluate fairness trade-offs.

## What I Did
- Designed and compared 8 neural network architectures
- Evaluated multiple batch sizes and optimizers (SGD, RMSProp, Adam)
- Applied dropout and L2 regularisation to reduce overfitting
- Performed grid search to identify optimal hyperparameters
- Analysed performance using confusion matrix and per-class metrics
- Conducted fairness analysis across gender and age groups

## Key Results

- Best model: Adam, batch size 64, 60 epochs
- Test Accuracy: 85.67%
- Strong performance on majority class (recall ~0.97)
- Lower recall for minority class (~0.41), highlighting class imbalance
- Minimal fairness gap across gender (~1–2%)

## Why This Matters

This project demonstrates an end-to-end machine learning workflow including experimentation, model selection, evaluation, and fairness analysis — reflecting real-world ML development practices.

## How to Run

1. Open `model_experiments.ipynb`
2. Take a Dataset (You're prefereable)
3. Run all cells
4. View results and analysis
