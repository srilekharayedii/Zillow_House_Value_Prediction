# Zillow_House_Value_Prediction
🧠 Anomaly Detection with Autoencoders - Credit Card Fraud Detection
This project demonstrates how to detect anomalies (fraudulent transactions) in credit card data using an Autoencoder neural network built with TensorFlow/Keras.

📁 Project Structure
Untitled6_(2).ipynb: Main Jupyter notebook containing:

Data preprocessing and visualization

Autoencoder model training with early stopping

Evaluation using classification metrics

Confusion matrix analysis

Visualization of reconstruction errors

📊 Dataset
Source: Kaggle - Credit Card Fraud Detection

Contains transactions made by European cardholders in September 2013

Highly imbalanced: ~0.17% frauds

Features are PCA-transformed except Time and Amount

🚀 Features Implemented
Standardization of Amount and Time

Train/test split with stratification

Autoencoder architecture with:

Input dimension matching original features

Hidden encoding/decoding layers

MSE-based loss and Adam optimizer

EarlyStopping callback after 19 epochs

Evaluation metrics: Precision, Recall, F1-score, Accuracy

Confusion matrix and anomaly distribution visualization

🔍 Key Observations
High precision and recall for fraudulent class

Lower recall for non-fraud due to class imbalance

Visualizations show clear separation in reconstruction error between fraud and non-fraud

Training stopped after 19 epochs due to early stopping criteria

🛠 Dependencies
bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
📌 How to Run
Download the dataset and place creditcard.csv in the same directory.

Open Untitled6_(2).ipynb in Jupyter Notebook or VSCode.

Run all cells sequentially to reproduce results.
