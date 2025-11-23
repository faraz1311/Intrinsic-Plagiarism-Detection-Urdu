# Intrinsic Plagiarism Detection for Urdu
A comprehensive repository for experiments, models, and analyses related to **Intrinsic Plagiarism Detection in Urdu language texts**.  
The project includes multiple classical ML and deep-learning pipelines, embedding techniques, ablation studies, and explainable AI work. All experiments are conducted using the Urdu Intrinsic Plagiarism Dataset available on Mendeley Data.

📂 **Dataset:** https://data.mendeley.com/drafts/rbpm4pw24r

---

## 🚀 Overview

This repository aims to explore how different feature extraction, embedding models, and machine-learning algorithms perform on **sentence-level intrinsic plagiarism detection** for Urdu.  
The project includes:

- Handcrafted linguistic feature extraction + ML models  
- Word2Vec and FastText embeddings  
- TF-IDF based sentence-level classification  
- Ablation analysis and feature importance  
- Explainable AI (XAI) for model interpretability  
- Multiple cross-validation settings  
- Domain-focused experiments (Moral Lessons, National Events)

---

## 📁 Repository Structure

### **1. Machine Learning + Feature Extraction**
Contains code for extracting handcrafted linguistic features such as:
- sentence length  
- lexical richness  
- POS-based features  
- stylometric features  
- character/word level statistics  
These features are trained using ML classifiers (Logistic Regression, SVM, Random Forest, XGBoost, etc.).

---

### **2. Word2Vec Sentence Level DL**
Deep-learning pipeline using:
- Pre-trained/custom Word2Vec embeddings  
- Sequential and deep neural models  
- Sentence-level vector aggregation  
- Classification for plagiarism detection  

---

### **3. TF-IDF Sentence Level ML**
Experiments using:
- Bag-of-Words  
- TF-IDF unigram, bigram, trigram features  
- Classical ML classifiers  
A strong baseline for the task.

---

### **4. Moral Lesson – All Experiments**
A subset of the dataset filtered for “Moral Lesson” topics.  
Includes all ML, DL, and embedding experiments performed specifically on this category to evaluate topic sensitivity.

---

### **5. Ablation and XAI**
A dedicated folder for:
- Ablation experiments (removing features to measure contribution)  
- SHAP / LIME / feature importance  
- Visualizations explaining model decisions  

---

### **6. FastText Sentence Level**
Sentence embeddings generated using:
- FastText skip-gram / CBOW models  
- Subword information for better Urdu morphology handling  
Trained with classical ML/DNN classifiers.

---

### **7. SFastText Sentence Level – Latest**
Improved/optimized pipeline using SFastText (Supervised FastText).  
Includes:
- hyperparameter tuning  
- improved text cleaning  
- optimized embedding dimensions  
- final updated results  

---

### **8. All Set CV Experiment 1**
Cross-validation experiment folder containing:
- K-Fold results  
- Training/validation logs  
- Metric comparisons across folds  

Supports reproducibility and performance reliability testing.

---

### **9. Word2Vec Sentence Level ML**
Word2Vec embeddings used with classical ML methods such as:
- SVM  
- Logistic Regression  
- Random Forest  
Comparing ML vs DL performance on same embeddings.

---

### **10. National Events – All Experiments**
Contains all experiments specific to the "National Events" category of the dataset.  
Useful for understanding model performance across different Urdu topical domains.

---

## 🧠 Models & Techniques Used

- **Classical ML:** Logistic Regression, SVM, Random Forest, XGBoost  
- **Deep Learning:** Dense Networks, BiLSTM/GRU (based on experiments)  
- **Embeddings:**  
  - Word2Vec (CBOW/Skip-Gram)  
  - FastText  
  - SFastText  
  - TF-IDF  
- **Feature Engineering:** Stylometric + linguistic features  
- **Explainability:** SHAP, LIME, Feature Importance  
- **Cross-Validation:** K-Fold, stratified splits  

---

## 📊 Evaluation Metrics
The following metrics are used across experiments:
- Accuracy  
- Precision, Recall, F1-score  
- Confusion Matrix  
- ROC-AUC (where applicable)

---

## 📥 Dataset

The Urdu Intrinsic Plagiarism Dataset is publicly available:

🔗 **Dataset Link:** https://data.mendeley.com/drafts/rbpm4pw24r

The dataset consists of:
- Plagiarized and non-plagiarized sentence pairs  
- Multiple domains including Moral Lessons & National Events  
- Balanced distribution of samples  

---

## 🎯 Purpose of This Repository

- Provide a unified experimental setup for Urdu intrinsic plagiarism detection  
- Compare performance across ML, DL, and embedding-based models  
- Analyze which linguistic or embedding features perform best  
- Offer reproducible experiments for researchers and students  
- Enable explainability (XAI) for transparent model decisions  

---

## 🧩 How to Use

1. Clone the repository  
2. Install dependencies from `requirements.txt`  
3. Download the dataset from Mendeley  
4. Run the experiments in the individual folders  
5. Compare evaluation metrics and visualizations  

---

## 📜 License
This project is open-source under the MIT License.

---

## 🤝 Contributions
Contributions, issues, and feature requests are welcome!  
Feel free to open a pull request.

---

## ⭐ Acknowledgment
Special thanks to the authors of the Urdu Intrinsic Plagiarism dataset and the open-source NLP tools used throughout this research.

