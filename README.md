# Iris-Dataset-Analysis

This Jupyter notebook performs automated machine learning (AutoML) analysis on the Iris dataset. Here’s a summary of its workflow:

1. **Library Installation & Imports**:  
   - Installs `mljar-supervised` for AutoML.
   - Imports necessary libraries from scikit-learn and mljar-supervised.

2. **Data Loading**:  
   - Loads the Iris dataset using `load_iris()` from scikit-learn.

3. **Feature & Target Extraction**:  
   - Extracts features (`X`) and target labels (`y`) from the dataset.

4. **Data Exploration**:  
   - Prints feature names and target class names for reference.

5. **AutoML Setup**:  
   - Configures an `AutoML` object to use the XGBoost algorithm with specific parameters, including fairness and explainability options.

6. **Model Training**:  
   - Fits the AutoML model on the Iris dataset.

**Purpose:**  
The notebook demonstrates how to use automated machine learning to classify iris species, with a focus on model selection, fairness, and explainability using the mljar-supervised library.