# Hope Speech Detection in Code-Mixed TULU

This repository contains a simple end-to-end pipeline for classifying code-mixed Tulu social media comments into four classes: encouraging, discouraging, uninvolved, and blended.  
We fine-tune a multilingual Transformer model (e.g., XLM-R or DistilBERT) on a labeled CSV file with `Text` and `Label` columns.  
The code includes basic text cleaning, label normalization, train/validation splitting, model training, and evaluation using accuracy and macro F1.  
Inference scripts are provided to generate predictions for a separate test CSV and save them as `predictions.csv`.  
All experiments are implemented in Python using HuggingFace Transformers, PyTorch, pandas, and scikit-learn.  
This project is meant as a reference implementation for hope-speech detection on low-resource, code-mixed data.
