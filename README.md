# Iris_Flower_Prediction

# Iris Flower Prediction Web App

A lightweight machine learning web application that uses a K-Nearest Neighbors (KNN) model to classify Iris flower species based on their physical measurements. The model is trained on the classic Iris dataset and served via a clean, responsive Flask web interface.

## 🚀 Features
* **Machine Learning Backend:** Powered by a K-Nearest Neighbors (KNN) classification model trained using `scikit-learn`.
* **Web Interface:** A responsive HTML/CSS frontend built with Python's Flask framework.
* **Instant Predictions:** Users can input sepal and petal measurements to instantly view the predicted species (*Setosa*, *Versicolor*, or *Virginica*).

---

## 🛠️ Tech Stack
* **Language:** Python
* **Web Framework:** Flask
* **Machine Learning:** Scikit-learn, NumPy
* **Frontend:** HTML5, CSS3

---

## 📂 Project Structure
```text
iris-classifier/
├── model/
│   ├── train_model.py     # Script to train and serialize the KNN model
│   └── iris_knn.pkl       # Saved trained model (Pickle file)
├── templates/
│   ├── index.html         # User input form
│   └── result.html        # Prediction output view
├── static/
│   └── style.css          # Frontend styling
├── app.py                 # Core Flask application
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
