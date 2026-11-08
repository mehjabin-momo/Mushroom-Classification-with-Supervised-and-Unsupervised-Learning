# Mushroom Classification with Supervised and Unsupervised Learning

A machine learning project that predicts whether a mushroom is **edible or poisonous** from its physical characteristics. Built in Python on Google Colab for the CSE422 course.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mehjabin-momo/Mushroom-Classification-with-Supervised-and-Unsupervised-Learning/blob/main/CSE422_PROJECT.ipynb)

## What it does

- **Data exploration:** missing values, class balance, and feature distributions
- **Preprocessing:** dropped 5 columns with over 60% missing data, filled the remaining gaps with the most frequent value, one-hot encoded categories, and scaled numbers
- **Supervised learning:** Decision Tree, Logistic Regression, K-Nearest Neighbors, and a Neural Network
- **Unsupervised learning:** K-Means clustering with 2 clusters, visualized with t-SNE
- **Model comparison:** accuracy, precision, recall, confusion matrices, and ROC curves

## Dataset

Mushroom dataset with 61,069 samples and 21 features (cap, gill, stem, habitat, season, etc.) and an edible/poisonous label. The classes are well balanced, so no resampling was needed.
[mushroom_dataset.csv](https://github.com/user-attachments/files/34540417/mushroom_dataset.csv)

## Results

| Model | Performance |
|---|---|
| Decision Tree | Above 99.9% accuracy |
| Neural Network | Above 99.9% accuracy |
| K-Nearest Neighbors | Above 98% accuracy |
| Logistic Regression | About 78% accuracy |

The non-linear models clearly beat Logistic Regression, which shows that the link between mushroom features and toxicity is complex and non-linear.

### Model performance comparison

<img width="924" height="653" alt="Screenshot 2026-11-08 145907" src="https://github.com/user-attachments/assets/6ce86c6b-a034-4eac-8c66-7c37b26156c8" />

### ROC curve comparison

<img width="726" height="582" alt="Screenshot 2026-11-08 145800" src="https://github.com/user-attachments/assets/5d6353b8-3c07-43a4-b674-b30ab86cb28a" />

## Tech used

- Python, pandas, NumPy
- scikit-learn, TensorFlow / Keras
- Matplotlib, Seaborn
- Google Colab

## Team

- Iftekhar Mohammed Aritro
- Mehjabin Mostare Momo

## Course

CSE422, BRAC University
