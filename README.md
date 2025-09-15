Crop Prediction using Machine Learning
Overview
This project aims to empower farmers by predicting the most suitable crops for cultivation using machine learning. By analyzing soil nutrients, weather patterns, and seasonal data, the model provides data-driven recommendations to enhance crop yield and profitability. The solution leverages Deep Neural Networks (DNNs) to deliver high accuracy predictions, surpassing traditional crop selection methods.
With a user-friendly interface, farmers can input key parameters and receive recommendations on the best crop to plant, along with the ideal cultivation period. This project demonstrates how AI can transform agriculture into a more efficient, informed, and sustainable practice.
________________________________________
Features
•	Predicts the best crop to cultivate based on soil and environmental conditions.
•	Simple and intuitive interface for farmers.
•	Supports multiple states and districts in India using geolocation data.
•	Provides insights into optimal planting months and seasons.
________________________________________
Dataset
The model uses multiple datasets to ensure robust predictions:
1.	Crop Prediction Dataset (Kaggle)
o	Contains 2200 samples covering 22 different crops.
o	Features include:
	Soil nutrients: Nitrogen (N), Phosphorus (P), Potassium (K), pH
	Weather parameters: Temperature, Humidity, Rainfall
o	Each crop has 100 samples, ensuring a balanced dataset.
2.	Rainfall in India Dataset
o	Cross-references geolocations with rainfall data to improve prediction accuracy.
Preprocessing steps:
•	Data cleaning to remove missing values.
•	Standardization of units and feature scaling.
•	Visualization to understand patterns between soil, weather, and crop yield.
________________________________________
Model Architecture
The model is a Deep Neural Network (DNN) implemented in PyTorch:
•	Input layer: 7 features (N, P, K, pH, Temperature, Humidity, Rainfall)
•	Hidden layers:
o	Layer 1: 64 neurons, SeLU activation
o	Layer 2: 128 neurons, SeLU activation
o	Layer 3: 64 neurons, SeLU activation
•	Output layer: 22 neurons (one per crop), Softmax activation
Training setup:
•	Train-test split: 80:20
•	Loss function: Categorical Cross-Entropy
•	Optimizer: Adam
•	Epochs: 100
•	Performance metric: Accuracy
________________________________________
Results
•	Training Accuracy: 99%
•	Test Accuracy: 99%
The high accuracy indicates that the model can reliably predict crops based on input features.
________________________________________
End-User Testing
The model accepts the following inputs to generate predictions:
•	Soil nutrients: N, P, K, pH
•	Geolocation: State and District
•	Cultivation month or season
Output: Recommended crop(s) for the provided inputs.

