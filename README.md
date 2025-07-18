# 🫀 Heart Disease Prediction Using Machine Learning

This project applies various Machine Learning (ML) classification models to predict the presence of heart disease in patients based on clinical features. Early detection of heart disease can significantly reduce the risk of complications and death. The models are trained and tested on a well-known public dataset sourced from Kaggle.

## 📊 Dataset

- Source: [Heart Disease Prediction Dataset](https://www.kaggle.com/datasets/sivagurunathan28/heart-prediction-disease-dataset)
- Total Records: 303
- Features: 13 clinical attributes such as age, chest pain type, cholesterol, max heart rate, etc.
- Target: `1` (has heart disease), `0` (no heart disease)

## 📌 Features Used

- Age
- Sex
- Chest Pain Type (`cp`)
- Resting Blood Pressure (`trtbps`)
- Cholesterol (`chol`)
- Fasting Blood Sugar (`fbs`)
- Resting ECG (`restecg`)
- Max Heart Rate (`thalach`)
- Exercise Induced Angina (`exang`)
- ST Depression (`oldpeak`)
- Slope of peak exercise ST segment (`slope`)
- Major vessels colored by fluoroscopy (`ca`)
- Thalassemia (`thal`)

## ⚙️ Technologies Used

- Python 3.x
- Jupyter Notebook
- Libraries:
  - `pandas`, `numpy` for data handling
  - `scikit-learn` for ML models
  - `matplotlib`, `seaborn` for visualization
- Optional UI: Flask / Streamlit for deployment

## 🔎 Machine Learning Models and Accuracy

| Model                  | Accuracy |
|------------------------|----------|
| Logistic Regression    | **89%**  |
| Support Vector Machine | 87%      |
| Naive Bayes            | 87%      |
| Random Forest          | 84%      |
| Decision Tree          | 79%      |

- **Logistic Regression**: Best performing model with linear separation capabilities.
- **SVM**: High generalization performance.
- **Naive Bayes**: Fast, simple, and effective with this dataset.
- **Random Forest**: Good ensemble performance.
- **Decision Tree**: Tends to overfit on smaller datasets.

## 🔁 Workflow

1. **Data Preprocessing**
   - Handle missing values
   - Encode categorical variables
   - Normalize numerical features

2. **Model Training & Testing**
   - 75% training and 25% testing split
   - Train all five models and evaluate using metrics

3. **Model Evaluation**
   - Accuracy, Confusion Matrix, and Visualizations (heatmaps, scatterplots)

4. **(Optional)**: Web UI for live predictions using Flask or Streamlit

## 🧠 Feature Importance

Key features impacting predictions include:

- Chest Pain Type (`cp`)
- ST Depression (`oldpeak`)
- Exercise Induced Angina (`exang`)
- Thalassemia (`thal`)

## 🌐 Deployment Options

- Flask / Django Web App
- Streamlit Dashboard
- Host on platforms like Heroku, AWS, or Google Cloud

## 🔐 Data Privacy Considerations

- Patient data is anonymized
- Security via HTTPS and access control
- Option for GDPR-compliant deployment

## 📈 Future Improvements

- Implement Deep Learning models (ANN, CNN)
- Add real-time wearable health data integration
- Build a mobile app for live monitoring and predictions

## 📄 Authors

- **Vamsi Chinta** – VIT-AP University – [sekhara.22bce9499@vitapstudent.ac.in](mailto:sekhara.22bce9499@vitapstudent.ac.in)
- **Mani Viswanadhula**
- **Karthikeya Gummadi**

## 📃 License

This project is open-source and free to use for educational purposes.

