# Fake-news-detection
## 📌 Project Overview
This project aims to detect whether a news headline is Real or Fake using a machine learning model.  
The model analyzes text data and predicts the credibility of news headlines.

Fake news detection is an important application in Natural Language Processing (NLP) and helps combat misinformation online.

---

## 🧠 Machine Learning Approach
The project follows these main steps:

1. Data preparation
2. Text preprocessing
3. Feature extraction
4. Model training
5. Model evaluation
6. Visualization of results

---

## 🗂 Dataset
A small dataset of news headlines was created for demonstration purposes.  
Each headline is labeled as:

- Real → legitimate news
- Fake → misleading or fabricated news

Example:

| Headline | Label |
|--------|--------|
| Scientists discover new planet | Real |
| Miracle cure spreads on social media | Fake |

---

## ⚙️ Technologies Used
The project was implemented using Python and the following libraries:

- pandas
- scikit-learn
- matplotlib
- seaborn

---

## 🔎 Feature Extraction
Text data was converted into numerical features using TF-IDF Vectorization, which measures the importance of words within the dataset.

---

## 🤖 Model
The model used for classification is:

Logistic Regression

It learns patterns in the text to distinguish between fake and real news headlines.

---

## 📊 Model Evaluation
The model performance was evaluated using:

- Accuracy Score
- Confusion Matrix
- Data Visualization

The confusion matrix helps analyze correct and incorrect predictions.

---

## 📈 Visualization
The project includes visualizations such as:

- Distribution of Real vs Fake news
- Confusion Matrix heatmap

These visualizations help better understand model performance.

---

## 🧪 Example Prediction
Example input:

Scientists discover water on Mars

Example output:

Real

---

## 🚀 Future Improvements
Possible improvements include:

- Using a larger dataset
- Adding more advanced NLP preprocessing
- Testing additional machine learning models
- Building a web interface for user interaction

---

## 👩‍💻 Author
Areej Alsalmi

This project was created as part of a learning journey in *Machine Learning and Natural Language Processing
