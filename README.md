<div align="center">

# 🛡️ Fingerprint Classification using Hybrid FLANN and Genetic Algorithm

### Evolutionary Machine Learning for Biometric Fingerprint Recognition

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green)
![TensorFlow](https://img.shields.io/badge/TensorFlow-orange)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-yellow)
![Genetic Algorithm](https://img.shields.io/badge/Genetic-Algorithm-red)
![Fingerprint Recognition](https://img.shields.io/badge/Biometrics-Fingerprint-purple)

</div>

---

# 📌 Overview

This project presents a **Hybrid Fingerprint Classification System** that combines a **Functional Link Artificial Neural Network (FLANN)** with a **Genetic Algorithm (GA)** to classify fingerprints from the NIST Fingerprint Database.

Unlike conventional neural networks, FLANN expands the input space using nonlinear basis functions, while the Genetic Algorithm optimizes the network weights to improve classification performance.

The project demonstrates how evolutionary optimization can enhance biometric recognition systems.

---

# 🎯 Objective

Develop an intelligent fingerprint classification model capable of accurately recognizing fingerprint patterns using:

- Functional Link Artificial Neural Network (FLANN)
- Evolutionary Optimization (Genetic Algorithm)
- Feature Engineering
- Principal Component Analysis (PCA)

---

# 📂 Dataset

**Dataset:** NIST Fingerprint Database

### Dataset Statistics

| Property | Value |
|----------|------:|
| Samples | 460 |
| Features | 152 |
| Classes | 5 |

### Fingerprint Classes

- Arch
- Left Loop
- Right Loop
- Tented Arch
- Whorl

---

# 🚀 Key Features

- Hybrid FLANN + Genetic Algorithm
- Nonlinear Feature Expansion
- PCA-based Feature Reduction
- Logistic Regression Weight Initialization
- Evolutionary Weight Optimization
- Multi-Class Fingerprint Classification
- Confusion Matrix Evaluation
- Accuracy Measurement

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming |
| NumPy | Numerical Computing |
| Pandas | Data Processing |
| Scikit-Learn | Machine Learning |
| PCA | Dimensionality Reduction |
| Logistic Regression | Initial Weight Generation |
| Matplotlib | Visualization |
| Genetic Algorithm | Optimization |

---

# 📂 Project Structure

```
Fingerprint-Classification/
│
├── data/
│     └── NIST DATABASE.csv
│
├── notebooks/
│
├── saved_models/
│
├── images/
│
├── README.md
│
└── Fingerprint_Classification.ipynb
```

---

# 🔄 Workflow

```
NIST Fingerprint Dataset
            │
            ▼
     Data Preprocessing
            │
            ▼
    Train-Test Split
            │
            ▼
   FLANN Feature Expansion
            │
            ▼
    Standardization
            │
            ▼
 Principal Component Analysis
            │
            ▼
 Logistic Regression
 (Weight Initialization)
            │
            ▼
 Genetic Algorithm
 Weight Optimization
            │
            ▼
 Optimized FLANN Model
            │
            ▼
 Fingerprint Prediction
```

---

# 🧠 Functional Link Artificial Neural Network (FLANN)

Unlike traditional neural networks, FLANN avoids hidden layers by expanding the feature space using nonlinear transformations.

### Feature Expansion

Original Features

```
152
```

Expanded Features

```
Original Features
Sin(x)
Cos(x)
Square(x)
```

This expansion allows the classifier to capture nonlinear relationships while maintaining a simple architecture.

---

# 🧬 Genetic Algorithm

The Genetic Algorithm is used to optimize the FLANN weights.

### Evolution Process

```
Initialize Population

↓

Fitness Evaluation

↓

Selection

↓

Crossover

↓

Mutation

↓

New Population

↓

Best Individual
```

### Fitness Function

The fitness score is based on:

- Classification Accuracy
- Weight Regularization

This prevents overfitting while improving prediction accuracy.

---

# 📉 Principal Component Analysis (PCA)

PCA is applied after feature expansion to:

- Remove redundant information
- Reduce dimensionality
- Improve computational efficiency
- Preserve 95% of the variance

---

# ⚙️ Machine Learning Pipeline

```
Dataset

↓

Feature Expansion

↓

StandardScaler

↓

PCA

↓

Logistic Regression

↓

Genetic Algorithm

↓

Optimized FLANN

↓

Prediction
```

---

# 📊 Results

### Model Performance

| Metric | Score |
|--------|-------:|
| Test Accuracy | **83.70%** |
| Classes | 5 |
| Dataset Samples | 460 |

---

# 📈 Evaluation Metrics

The project evaluates the model using:

- Accuracy Score
- Confusion Matrix
- Prediction Analysis

---

# 🖼️ Sample Prediction Pipeline

```
Fingerprint Features

↓

Feature Expansion

↓

Scaling

↓

PCA

↓

Optimized FLANN

↓

Fingerprint Class
```

---

# 💡 Skills Demonstrated

- Machine Learning
- Evolutionary Algorithms
- Genetic Algorithm
- FLANN
- Feature Engineering
- PCA
- Pattern Recognition
- Biometrics
- Classification
- Data Preprocessing
- Python
- Scikit-Learn

---

# 📚 Learning Outcomes

Through this project, I learned:

- Functional Link Artificial Neural Networks
- Evolutionary Optimization
- Genetic Algorithms
- Feature Space Expansion
- Principal Component Analysis
- Weight Optimization
- Pattern Recognition
- Biometric Classification
- Model Evaluation
- Hyperparameter Tuning

---

# 🚀 Future Improvements

- Deep Learning-based Fingerprint Recognition
- Convolutional Neural Networks
- Siamese Networks
- Transfer Learning
- Feature Selection using GA
- Real-Time Fingerprint Recognition
- Flask API Deployment
- Streamlit Dashboard
- Model Explainability (SHAP/LIME)
- Cross-Validation & Hyperparameter Optimization

---

# ⭐ Repository Highlights

✔️ Hybrid Machine Learning Model

✔️ Evolutionary Optimization

✔️ FLANN Architecture

✔️ Genetic Algorithm Implementation

✔️ PCA Feature Reduction

✔️ Biometric Classification

✔️ Well-Structured ML Pipeline

---

# 🤝 Contributing

Contributions are welcome!

Feel free to fork this repository and submit a pull request.

---

# 📄 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

## Biswaranjan Chakra

**Aspiring Data Engineer | Machine Learning Engineer**

### Skills

- Python
- SQL
- Machine Learning
- Deep Learning
- TensorFlow
- Scikit-Learn
- Apache Airflow
- PySpark
- Data Engineering

---

## ⭐ If you found this project useful, please consider giving it a Star!
