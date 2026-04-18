# 🌸 Naive Bayes Classifier from Scratch (Iris Dataset)

🚀 A from-scratch implementation of the Naive Bayes algorithm in Python, applied to the classic Iris dataset for multi-class classification.

---

## 📌 Problem Statement

The goal of this project is to classify iris flowers into three species:
- Setosa  
- Versicolor  
- Virginica  

using a probabilistic machine learning approach built entirely from scratch.

---

## 📊 Dataset

This project uses the **Iris dataset**, a well-known dataset in machine learning containing:

- 150 samples  
- 3 classes (species)  
- 4 features:
  - Sepal length  
  - Sepal width  
  - Petal length  
  - Petal width  

---

## 💡 Key Features

- ✅ Implemented completely from scratch (no scikit-learn)  
- ✅ Uses Gaussian Naive Bayes for continuous features  
- ✅ Multi-class classification support  
- ✅ Clean and modular code structure  
- ✅ Easy to understand and extend  

---

## 📊 Mathematical Foundation

The classifier is based on Bayes' Theorem:

P(C | X) = (P(X | C) * P(C)) / P(X)

Assumption:
> Features are conditionally independent given the class label

---

## 🧪 Implementation Details

- Mean and variance computed per feature per class  
- Gaussian distribution used for likelihood estimation  
- Priors calculated from class frequencies  
- Prediction based on maximum posterior probability  

---

## 📈 Results

- Successfully classifies iris flowers into three species  
- Achieves an accuracy of **~95%** 

---

## 🎯 Skills Demonstrated
- Probability & statistics (Gaussian distribution, Bayes' theorem)
- Machine learning from first principles
- Multi-class classification
- Data handling and preprocessing

---

## 🔮 Future Improvements
- Add Laplace smoothing
- Compare results with scikit-learn implementation
- Add confusion matrix and visualization
- Extend to other datasets

---

## 🎯 Relevance to Data Science Roles

This project demonstrates:

- Strong foundational understanding of ML algorithms
- Ability to implement models without relying on libraries
- Solid analytical and problem-solving skills
  
---

## 📜 License

This project is licensed under the MIT License.

