# 🎫 AI Ticket Classification System

### NLP-Based Customer Support Ticket Category & Priority Prediction

## 📌 Project Overview

The **AI Ticket Classification System** is a Machine Learning and Natural Language Processing project that automatically classifies customer support tickets into different **categories** and **priority levels**.

The system helps organize customer support requests and can assist support teams in handling tickets more efficiently.

## 🎯 Objectives

* Automatically classify customer support tickets.
* Predict the category of each ticket.
* Predict the priority level of each ticket.
* Apply NLP techniques to text data.
* Evaluate Machine Learning model performance.

## 📊 Dataset

The project contains **70 customer support tickets**.

### Ticket Categories

* Account
* Delivery
* Feedback
* Payment
* Refund
* Subscription
* Technical

### Priority Levels

* High
* Medium
* Low

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Natural Language Processing (NLP)
* TF-IDF Vectorization
* Logistic Regression
* Matplotlib
* Jupyter Notebook

## 🔄 Machine Learning Workflow

```text
Customer Support Ticket
          ↓
Text Preprocessing
          ↓
TF-IDF Vectorization
          ↓
Logistic Regression
          ↓
Prediction
          ↓
Model Evaluation
```

## 🤖 Models Used

### 1. Category Classification

The Category Classification model predicts the type of customer support ticket.

**Model:** Logistic Regression

**Features:** TF-IDF text features

**Accuracy:** 78.57%

### 2. Priority Classification

The Priority Classification model predicts whether a ticket has High, Medium, or Low priority.

**Model:** Logistic Regression

**Features:** TF-IDF text features

**Accuracy:** 71.43%

## 📈 Model Performance

| Model                   | Accuracy | Precision | Recall | F1 Score |
| ----------------------- | -------: | --------: | -----: | -------: |
| Category Classification |   78.57% |    88.10% | 78.57% |   78.10% |
| Priority Classification |   71.43% |    55.95% | 71.43% |   62.71% |

> Note: Category and Priority are separate prediction tasks, so their metrics should be interpreted independently.

## 📏 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## 📁 Project Files

```text
AI-Ticket-Classification-System/
│
├── AI_Ticket_Classification.ipynb
├── category_confusion_matrix.png
├── priority_distribution.png
├── priority_model_results.csv
├── model_comparison.csv
└── README.md
```

## 🚀 How to Run

1. Clone or download this repository.
2. Open `AI_Ticket_Classification.ipynb` in Jupyter Notebook or JupyterLab.
3. Install the required Python libraries.
4. Run the notebook cells sequentially.
5. Review the predictions and model evaluation results.

## 🔮 Future Improvements

* Increase the size of the training dataset.
* Apply advanced NLP preprocessing.
* Experiment with different Machine Learning algorithms.
* Use transformer-based models such as BERT.
* Improve priority classification performance.
* Deploy the model as a web application or API.

## 👨‍💻 Author

**Adarsh Prabhakar**

AI/ML Learner | Data Science & Machine Learning

