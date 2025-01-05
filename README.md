# Crop Recommendation Using Machine Learning Model (Cat-Boost) with 99.55% Accuracy

This repository provides a **Crop Recommendation System** using the **CatBoost Classifier**, achieving an exceptional accuracy of **99.55%**. The system leverages agricultural data to recommend the most suitable crop based on environmental and soil parameters, empowering farmers and agricultural researchers to make informed decisions for optimizing crop yield.

---

## Features

- **High Accuracy:** Utilizes the powerful **CatBoost algorithm** to achieve a classification accuracy of 99.55%.
- **Multi-Class Classification:** Predicts the best crop to grow from multiple classes based on input parameters.
- **Preprocessing:** Encodes categorical labels and splits data into training and testing sets for model training and evaluation.
- **Model Evaluation:**
  - Confusion Matrix for visualizing prediction accuracy.
  - Classification Report for detailed performance metrics.
  - ROC-AUC curves to assess model performance for each class.
- **Visualization Tools:** Uses Matplotlib and Seaborn to create insightful plots for better understanding.
- **Real-Time Predictions:** Allows testing with new data to recommend the most suitable crop.
- **Model Persistence:** Saves the trained model for future use.

---

## Dataset

The dataset, named `Crop_recommendation.csv`, includes agricultural and environmental parameters such as:

- **Soil Nutrients:** Nitrogen (N), Phosphorus (P), Potassium (K)
- **Environmental Conditions:** Temperature, Humidity, pH, Rainfall
- **Label:** Recommended crop

---

## Installation and Dependencies
**1. Clone the repository:**
   ```bash
   git clone https://github.com/jijan67/Crop-Recommendation-System-Using-CatBoost-Classifier-Model.git
   cd Crop-Recommendation-System-Using-CatBoost-Classifier-Model
   ```
**2.Install the required Python libraries:**
   ```bash
   pip install catboost numpy pandas matplotlib seaborn scikit-learn
   ```
**3.Place the Crop_recommendation.csv dataset in the root directory.**

## Key Results
- Achieved 99.55% accuracy on test data.
- Visualized the model’s performance through a classification report, confusion matrix, and ROC curves.
- Demonstrated the model's ability to recommend crops based on given parameters.

## Future Enhancements
- Integration with real-time IoT devices for automated data input.
- Expand dataset to include more crops and environmental parameters.
- Deploy the system as a web or mobile application for ease of access.

## Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests for enhancements or bug fixes.

## Acknowledgements
Special thanks to the open agricultural datasets and the developers of CatBoost and scikit-learn for making this project possible.
