# 🌸 Iris Species Detection — Machine Learning with Multiclass Perceptron

Welcome to *Iris Species Detection*, a passion project that blends classical machine learning with a thoughtful, human touch. This project classifies the species of Iris flowers—Setosa, Versicolor, or Virginica—based on their physical measurements, using a Multiclass Perceptron algorithm built entirely from scratch (no scikit-learn shortcuts here!).

> ✨ This repository isn't just code. It's a reflection of hands-on exploration, a commitment to learning, and a story of growth through every weight update.

---

## 🔍 About the Project

At its heart, this project is about understanding **how** a machine learns, not just seeing it happen. Rather than importing a pre-built model, I implemented the **Multiclass Perceptron algorithm manually**, controlling every part of the process from data preprocessing to model evaluation and visualization.

The dataset used is the classic [Iris dataset](https://en.wikipedia.org/wiki/Iris_flower_data_set), consisting of 150 samples with 4 features each:
- Sepal length
- Sepal width
- Petal length
- Petal width

The goal? Predict the correct species of the Iris flower using only these four features.

---

## 🧠 How It Works

### 📥 1. Data Preparation
- Loaded using **pandas** and stored as a DataFrame.
- Randomly split into **training** and **testing** sets using `.sample()`.

### ⚙️ 2. Algorithm: Multiclass Perceptron (from scratch!)
- Each class (Setosa, Versicolor, Virginica) is initialized with its own weights.
- Uses **weighted sums** to predict the class of each flower.
- During training, weights are updated manually using the **Perceptron learning rule**:
  - Increase weights for the correct class
  - Decrease weights for the wrongly predicted class
- Training continues **until convergence**, ensuring accuracy improves over time.

### 📊 3. Model Evaluation
- Calculates overall **accuracy** and constructs a **confusion matrix**.
- **Matplotlib** is used to visualize accuracy across different configurations.

---

## 📁 Project Structure
```
.
├── algorithm.txt   # Step-by-step breakdown of the algorithm
├── iris_dataset.csv   # The Iris flower dataset
├── model.ipynb   # Jupyter notebook containing the full implementation
└── README.md   # (You are here!)
```

---

## 👥 Team Members & Roles

| Name                   | Role                          |
|------------------------|-------------------------------|
| Samuel T. Gunawan      | Project Manager               |
| [Priska A. Likarsa](https://github.com/priskaaimee)      | Developer, Data Analyst       |
| [Jorel A. Setiabudi](https://github.com/jorelalexander)     | Developer, Data Analyst       |
| [Evan A. Chandra](https://github.com/shifinn)        | Developer, Data Analyst       |

> _Looking to grow the team! If you're interested in machine learning, data visualization, or collaborative coding—reach out!_

---

## 🌱 Future Works

This project is just the beginning. Here's what’s coming next:

- 🚀 **Model Comparison**: Implement other algorithms (e.g., SVM, KNN, Decision Trees) for performance benchmarking.
- 📊 **Advanced Visualizations**: Introduce confusion matrix heatmaps, 3D scatter plots of decision boundaries, and epoch-wise performance animations.
- 🧪 **Hyperparameter Tuning**: Automate learning rate selection and explore regularization.
- 🗃️ **Web Deployment**: Package the model and deploy a simple interactive web app using Flask or Streamlit.
- 📝 **AutoML Version**: Incorporate pipeline building and auto-training with tools like Optuna or Auto-sklearn.

---

## 🚀 Why This Matters

This repo is more than just a classifier—it's a teaching tool, a statement of intention, and a demonstration of core machine learning concepts without relying on black-box libraries. 

Whether you're a recruiter, a fellow developer, or an enthusiast diving into machine learning—this project aims to inspire clarity, curiosity, and confidence.

---

## 🤝 Let's Connect

Have questions, feedback, or just want to say hi? Feel free to reach out via [Instagram](https://www.instagram.com/sam__gunawan/) or fork the repo and contribute your ideas.

---

> *"The best way to learn is to build. The best way to build is to share."*  
> — This repository lives by that philosophy.
