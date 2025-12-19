📡 OPS-SAT Satellite Anomaly Detection using Machine Learning

A Predictive Analytics Project using ESA OPS-SAT Telemetry Dataset

📌 Overview

This project applies modern predictive analytics techniques to detect anomalies in satellite telemetry data collected from the ESA OPS-SAT spacecraft, available on Zenodo.

Using multiple machine learning models (Logistic Regression, SVM, Random Forest, Naïve Bayes, Decision Tree & KNN), the project identifies signal behaviour patterns to classify whether a satellite signal segment is anomalous or normal.

This repository contains:

Dataset preprocessing scripts

Exploratory data analysis

Model training and evaluation

Visual results and interpretation

Jupyter notebooks and final project report

🚀 Dataset Source

Dataset Name: OPS-SAT Satellite Telemetry Anomaly Dataset
Provider: European Space Agency
Download Link:
🔗 https://zenodo.org/records/15108715

The dataset consists of signal statistics derived from OPS-SAT spacecraft communication channels including peaks, skewness, kurtosis, variance, and duration attributes.

🔍 Objectives

Detect satellite telemetry anomalies using classification ML models

Perform EDA and correlation analysis

Visualise PCA feature distribution

Compare multivariate model performance

Identify the best predictive model

🧠 Machine Learning Models Used

Logistic Regression

Support Vector Machine

Random Forest

Decision Tree

K-Nearest Neighbour

Naive Bayes

📊 Key Visualizations

Class Distribution Plot

Correlation Heatmap

PCA Projection

Accuracy Comparison Chart

Visual outputs are included in the notebook.

🧾 Results Summary
Model	Accuracy
Random Forest	~97%
SVM	~95%
Decision Tree	~94%
Logistic Regression	~92%
KNN	~90%
Naive Bayes	~85%

🏆 Random Forest performed the best overall.

🛠️ Requirements

Install dependencies using:

pip install -r requirements.txt


Libraries used:

pandas
numpy
matplotlib
seaborn
scikit-learn

▶️ How to Run

Clone repository:

git clone https://github.com/<username>/ops-sat-anomaly-detection.git


Open notebook:

jupyter notebook OPS_SAT_Clean.ipynb


Run all cells to:

preprocess dataset

train models

view visual output

read conclusions

🛰️ About OPS-SAT Mission

OPS-SAT is a 3U CubeSat launched by ESA to test new mission control and space communication technologies.
The satellite continuously transmits experimental telemetry signals, enabling academic research in machine learning anomaly detection.

🧩 Use Cases

Spacecraft fault detection

Communication system stability testing

Predictive maintenance

Space engineering research

Mission control monitoring

📌 Future Improvements

LSTM / RNN models for time-series data

Explainable AI (SHAP, LIME)

Deployment on cloud / APIs

Real-time anomaly monitoring framework

Dataset expansion using ESA missions

📜 License

This project uses open research data from ESA under Zenodo dataset licensing.

🧑‍💻 Author

Your Name Here
Predictive Analytics Engineer / ML Developer
📧 Email: ___________

⭐ GitHub Stars Appreciated!

If this project helps you, kindly ⭐ star the repository!
