# Machine-Learning-in-Genomic-Variations-and-Disease-Risk-Modeling-
This Python program leverages several key libraries to predict disease outcomes based on genomic data. It uses Tkinter to create a simple GUI for file selection and processes the data with pandas to load and manipulate it. The data is normalized with scikit-learn, and a neural network is built using TensorFlow. The model, consisting of multiple layers and a sigmoid activation function, predicts whether an individual has a disease (1) or not (0). After training, the model is evaluated on test data, and metrics like accuracy and AUC (Area Under the Curve) are printed to assess performance. Matplotlib is used to visualize predictions, such as a scatter plot displaying disease predictions (0 or 1). Additionally, the SHAP library provides insights into which gene variations had the most influence on the predictions. The entire workflow, from loading data to training and evaluation, is automated for easy genomic data analysis.

# Features
1. GUI for file selection: Simple interface for loading genomic data.
2. Data processing: Handles normalization and splitting using pandas and scikit-learn.
3. Neural Network: Built using TensorFlow for binary disease prediction.
4. Visualization: Uses matplotlib to display predictions and model performance.
5. Model Explainability: Uses SHAP to provide insights into gene feature importance.

# Installation
1. Clone the Repository
2. Install Dependencies
3. Run the Program
