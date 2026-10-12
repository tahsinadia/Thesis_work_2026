# Thesis_work_2026
# Distinguishing Loneliness from Depression Using Linguistic and Explainable Machine Learning Analysis of Online Mental Health Discourse

**Author:** Tahsina Hasnat Dia

## 📌 Overview

This thesis investigates how loneliness and depression can be distinguished through linguistic patterns in online mental health discourse using machine learning (ML), natural language processing (NLP), and explainable artificial intelligence (XAI).

Although loneliness and depression may share similar linguistic expressions, they represent distinct experiences. This research explores their linguistic differences and evaluates how machine learning models can identify meaningful patterns in text.

## 🎯 Research Objectives

- Identify linguistic differences between loneliness and depression in online text.
- Develop and evaluate machine learning and transformer-based models for text classification.
- Investigate the contribution of linguistic, sentiment, readability, and psychological features.
- Apply explainable AI techniques to interpret model predictions and identify influential features.

## 📊 Datasets

This research consists of two experimental studies:

### Experiment 1: Reddit Mental Health Discourse

An online mental health discourse dataset containing posts associated with depression and loneliness.

- Depression posts: 115,283
- Loneliness posts: 22,304
- Undersampled dataset: 44,608 posts

**Feature engineering includes:**
- TF-IDF text representations
- LIWC-inspired linguistic and psychological features
- VADER sentiment analysis
- Readability measures
- Psychological and linguistic indicators

### Experiment 2: DepressionEmo Dataset

A multi-class emotion classification dataset used to investigate emotion-related linguistic patterns and the classification of loneliness and depression.

The experiment evaluates transformer-based language models on text classification tasks.

## 🧠 Methodology

The research follows a structured NLP and machine learning pipeline:

1. Data collection and preprocessing
2. Exploratory data analysis
3. Feature extraction and engineering
4. Feature selection and dimensionality reduction
5. Machine learning model training and evaluation
6. Transformer-based text classification
7. Explainability analysis using SHAP
8. Comparative evaluation of model performance

## 🤖 Models and Techniques

**Traditional Machine Learning**
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- XGBoost

**Transformer-Based Models**
- BERT
- RoBERTa
- MentalBERT
- ClinicalBERT

**Explainable AI**
- SHAP (SHapley Additive exPlanations)

**Evaluation Metrics**
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

## 📈 Key Findings

### Experiment 1

- Random Forest achieved a ROC-AUC of **0.9106** in distinguishing depression-related and loneliness-related discourse.
- Linguistic features, including `isolation_total` and selected TF-IDF features, emerged as important predictors.
- SHAP was used to investigate how features contributed to model predictions.

### Experiment 2

- RoBERTa achieved a micro-F1 score of **0.8286** in the evaluated classification task.
- Loneliness-related classification performance reached approximately **0.8351–0.8499 F1**, depending on the reported evaluation.
- ClinicalBERT showed comparatively lower performance in the evaluated setting.

*Note: Final reported metrics should be verified against the corresponding experiment's evaluation results before publication.*

## 🛠️ Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn
- NLP and text preprocessing tools
- Transformer-based language models
- SHAP
- Data visualization libraries

## 🔬 Research Contribution

This thesis explores the use of linguistic analysis, traditional machine learning, transformer architectures, and explainable AI to investigate the distinction between loneliness and depression in online discourse.

The work emphasizes interpretable linguistic patterns alongside predictive performance, supporting a more nuanced understanding of how these experiences are expressed through text.

**Important:** The models are research tools and are not intended to provide clinical diagnoses.

## 📁 Repository Structure

```text
thesis-project/
├── data/
│   └── README.md
├── notebooks/
│   ├── experiment_1/
│   └── experiment_2/
├── models/
├── results/
├── figures/
├── requirements.txt
└── README.md
```

*The directory structure is a suggested template and should be adjusted to match the actual repository.*

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <YOUR_REPOSITORY_URL>
cd <YOUR_REPOSITORY_NAME>
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Explore the experiments

Open the notebooks in the `notebooks/` directory and follow the documented preprocessing, modeling, evaluation, and explainability workflows.

Dataset access and execution instructions should be added according to the relevant dataset licenses and availability.

## ⚖️ Ethical Considerations

This research analyzes online mental health discourse. Responsible use of the data requires respecting dataset licenses, privacy considerations, platform policies, and the limitations of automated text classification.

Predictions should not be interpreted as definitive evidence of an individual's psychological state.

## 👩‍💻 Author

**Tahsina Hasnat Dia**
**Rasidul Hoquec Chowdhury**

Computer Science and Engineering  
Leading University, Sylhet, Bangladesh

Research interests: Natural Language Processing (NLP), Machine Learning, Explainable AI, Human-Computer Interaction, and human-centered AI research.

---

*This repository documents thesis research on distinguishing loneliness from depression through linguistic and explainable machine learning analysis of online mental health discourse.*