# IPL Classification: Predicting RCB Match Outcomes

This project analyzes IPL match data to predict whether the Royal Challengers Bangalore (RCB) team will win or lose a match based on match-level features. It applies classification models from scikit-learn to train and evaluate predictive performance.

---

## 📌 Project Objective

To build a machine learning model that classifies IPL matches played by RCB as **win** or **loss**, based on key match attributes like venue, toss decision, opponent, and more.

---

## 📂 Datasets Used

- `matches.csv`: Contains match-level data like team names, toss results, venue, and match result.
- `deliveries.csv`: Not directly used in the model, but can provide granular ball-by-ball insights if needed.

Data Source: [Kaggle IPL Dataset](https://www.kaggle.com/datasets)

---

## 🛠️ Features Used

- `venue`
- `toss_decision`
- `toss_winner`
- `opponent`
- `match_winner` (Target)

---

## 🧠 ML Techniques

The notebook performs the following:
- Data filtering for RCB matches
- Feature encoding and preprocessing
- Model training using:
  - Logistic Regression
  - Accuracy score for evaluation

You can easily extend it with more classifiers like Decision Trees, Random Forests, or SVMs.

---

## ▶️ How to Run This Project

## ▶️ How to Run This Project

1. **Clone this repository**:
   ```bash
   git clone https://github.com/yourusername/ipl-classification.git
   cd ipl-classification
#2.0pen the notebook
Launch it using Jupyter or Google Colab.
2.pip install pandas numpy matplotlib scikit-learn
