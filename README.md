# 🏃 Fitness Activity Recognition Using Machine Learning

## 📌 Overview

Fitness Activity Recognition is a machine-learning project that identifies a person's physical activity using sensor data.

The system analyzes accelerometer, gyroscope, heart-rate, and step-count features to classify activities such as Walking, Running, Cycling, Swimming, and Standing.

## 🎯 Objectives

* Recognize physical activities automatically
* Process wearable sensor data
* Train a machine-learning classification model
* Predict activities from new sensor readings
* Provide a simple Streamlit interface
* Demonstrate the use of AI in fitness applications

## 🧠 Activities

The model recognizes:

* Walking
* Running
* Cycling
* Swimming
* Standing

## 🏗️ System Architecture

```text
Sensor Data
     ↓
Data Collection
     ↓
Data Preprocessing
     ↓
Feature Scaling
     ↓
Random Forest Classifier
     ↓
Activity Prediction
     ↓
Fitness Dashboard
```

## 📊 Input Features

The model uses:

* Acceleration X
* Acceleration Y
* Acceleration Z
* Gyroscope X
* Gyroscope Y
* Gyroscope Z
* Heart Rate
* Steps

## 🤖 Machine Learning Algorithm

The project uses a **Random Forest Classifier**.

Random Forest is suitable for this project because it can handle multiple numerical sensor features and provides a strong baseline for classification.

## 🛠️ Technologies

* Python
* NumPy
* Pandas
* Scikit-learn
* Joblib
* Streamlit
* GitHub

## 📁 Project Structure

```text
fitness-activity-recognition/
│
├── data/
│   └── fitness_activity_data.csv
│
├── model/
│   ├── activity_model.pkl
│   └── scaler.pkl
│
├── src/
│   ├── train_model.py
│   └── predict_activity.py
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/fitness-activity-recognition.git
```

Open the project:

```bash
cd fitness-activity-recognition
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Train the Model

Run:

```bash
python src/train_model.py
```

This creates the dataset, trains the Random Forest model, evaluates it, and saves the model files.

## 🔮 Make Predictions

Run:

```bash
python src/predict_activity.py
```

Enter sensor values when prompted.

The system will return the predicted activity.

## 🌐 Run the Web Application

Run:

```bash
streamlit run app.py
```

The Streamlit interface allows users to enter sensor values and obtain an activity prediction.

## 📈 Results

The model can classify the activities included in the training dataset.

For a real-world implementation, evaluation should be performed using an independent real sensor dataset and metrics such as:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

The included demonstration uses synthetic data, so its performance should not be interpreted as real-world wearable-device accuracy.

## 💡 Applications

* Fitness tracking
* Smartwatch activity recognition
* Sports analytics
* Workout monitoring
* Mobile fitness applications
* Activity-based calorie estimation
* General physical activity monitoring

## ✅ Advantages

* Simple and easy to understand
* Fast machine-learning predictions
* Easy to deploy
* Supports multiple activities
* Can be extended to real-time systems
* Suitable for academic demonstration

## ⚠️ Limitations

* Demonstration uses synthetic data
* Limited activity categories
* Sensor noise may affect predictions
* Does not currently connect to a physical wearable
* Individual movement differences can affect classification

## 🚀 Future Improvements

* Use real wearable sensor datasets
* Add CNN/LSTM/GRU models
* Implement real-time sensor streaming
* Connect smartphones and smartwatches
* Add more activities
* Develop personalized activity models
* Add calorie-burn estimation
* Add a real-time analytics dashboard
* Deploy the model as a cloud API

## 👩‍💻 Author

**Your Name**

B.Tech – Artificial Intelligence and Data Science

## ⭐ Conclusion

The Fitness Activity Recognition system demonstrates how machine learning can be used to recognize human physical activities from sensor data.

The project provides a foundation for developing intelligent fitness applications, wearable-device systems, and real-time activity monitoring solutions.
