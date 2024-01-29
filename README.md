Introduction:
This project focuses on utilizing machine learning for disease prediction based on symptoms, aiming to assist in clinical settings for early diagnosis and intervention. 
The dataset employed here comprises disease-symptom relationships, with a particular emphasis on the severity of symptoms. 
The goal is to train a machine learning model to predict the likelihood of specific diseases given a set of symptoms, contributing to faster and more accurate clinical decision-making.

Dataset:
Disease Dataset
Size: 4920 samples, 18 features
Features: Diseases, Symptom_1 to Symptom_17
Description: The dataset contains information on various diseases and associated symptoms. Some symptoms have different severity levels, contributing to a more nuanced understanding of the data.
Symptom Severity Dataset
Symptoms were assigned severity weights based on the Symptom Severity dataset. This allowed for a more nuanced representation of symptom influence in the prediction model.
Machine Learning Model
Random Forest Classifier
A Random Forest Classifier was employed for disease prediction, leveraging an ensemble of decision trees for accurate and robust results.
Evaluation Metrics
The model was evaluated using precision, recall, and F1-score, providing insights into its predictive performance across different diseases.

Results:
The model demonstrated high accuracy and F1-score, indicating its effectiveness in predicting diseases based on symptoms.
Testing the model with a set of symptoms resulted in accurate predictions, showcasing its potential for real-world clinical applications.
Usage
This machine learning model can be integrated into clinical systems to support healthcare professionals in diagnosing diseases based on patient symptoms. 
The severity-weighted symptom approach enhances the model's ability to capture the nuanced relationships between symptoms and diseases.

