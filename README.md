

# Heart Disease Prediction Using Ensemble Learning Model

This project focuses on predicting heart disease using an ensemble learning model, leveraging multiple machine learning algorithms to enhance prediction accuracy. The model aims to assist in early detection and preventive care strategies for cardiovascular health.

![Heart Disease Prediction](https://user-images.githubusercontent.com/95960866/229347650-fdfb3ec7-cb85-4990-8930-bee2b6c22db0.jpg)

## Overview

Heart disease is one of the leading causes of death worldwide, and early detection is crucial for improving outcomes. This project uses ensemble learning, combining several classifiers to build a robust model capable of predicting the presence of heart disease based on patient data.

### Key Features:
- **Ensemble Learning**: Integration of multiple classifiers including Decision Trees, Random Forests, and Support Vector Machines.
- **Data Preprocessing**: Handling missing values, feature selection, and normalization.
- **Model Evaluation**: Assessment using metrics like accuracy, precision, recall, and F1-score.

## Datasets

The dataset used in this project is sourced from the UCI Machine Learning Repository's Heart Disease dataset. The dataset includes information on patient demographics, lifestyle habits, and various medical attributes related to cardiovascular health.

### Dataset Source:
- **URL**: [Heart Disease Databases](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

### Data Attributes:
- **Key Attributes Used**:
  - Age
  - Sex
  - Chest pain type (cp)
  - Resting blood pressure (trestbps)
  - Serum cholesterol (chol)
  - Fasting blood sugar (fbs)
  - Resting electrocardiographic results (restecg)
  - Maximum heart rate achieved (thalach)
  - Exercise-induced angina (exang)
  - ST depression induced by exercise (oldpeak)
  - Slope of the peak exercise ST segment (slope)
  - Number of major vessels colored by fluoroscopy (ca)
  - Thalassemia (thal)
  - Diagnosis of heart disease (num)

## Methodology

1. **Data Collection and Preprocessing**:
   - Collected and cleaned the dataset by handling missing values and performing feature selection.
   - Normalized data to ensure all features contribute equally to the model.

2. **Model Development**:
   - Implemented an ensemble learning approach using Python and scikit-learn.
   - Combined multiple classifiers (Decision Trees, Random Forests, SVMs) to create a robust predictive model.

3. **Model Training and Evaluation**:
   - Split the data into training and testing sets.
   - Trained the model using the training set and evaluated its performance on the testing set using accuracy, precision, recall, and F1-score.

4. **Prediction and Analysis**:
   - The model predicts the likelihood of heart disease based on the input features.
   - Analyzed model performance and identified the most significant features contributing to the prediction.

## Results

The ensemble model achieved a high accuracy rate in predicting heart disease, demonstrating the effectiveness of using multiple classifiers for medical diagnosis.

## Conclusion

This project highlights the potential of machine learning, particularly ensemble learning, in healthcare applications. By accurately predicting heart disease, the model can serve as a valuable tool for healthcare providers, enabling early intervention and personalized treatment plans.

## How to Run

1. Clone the repository.
2. Install required Python libraries using `pip install -r requirements.txt`.
3. Run the `heart_disease_prediction.py` script to train the model and make predictions.

## Future Work

- Integrating more advanced models like deep learning for improved accuracy.
- Expanding the dataset to include more diverse patient demographics.
- Implementing a user-friendly interface for healthcare providers to use the model in clinical settings.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
