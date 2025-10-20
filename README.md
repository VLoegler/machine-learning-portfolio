# Machine Learning Portfolio

A collection of machine learning and deep learning projects applying core ML methods to genomics and transcriptomics data. Each notebook demonstrates end-to-end workflows including preprocessing, modeling, evaluation, and interpretation.

## Technologies

`scikit-learn` · `PyTorch` · `XGBoost` · `SHAP` · `NumPy` · `Pandas` · `Matplotlib`

---

## Projects

### 1. Human Ancestry Prediction from SNP Data  
**Notebook:** `1000genomesAncestry.ipynb`  
**Goal:** Predict ancestry from SNP data.  
**Models:** KNN, Random Forest, Dense Neural Network, Neural Network Ensemble  
**Focus:** Feature encoding, supervised classification, ensemble learning.

---

### 2. Explainable Breast Cancer Subtype Classification  
**Notebook:** `BreastCancerClassification.ipynb`  
**Goal:** Classify breast cancer samples into PAM50 subtypes.  
**Models:** XGBoost, Dense Neural Network  
**Focus:** Multi-class classification and interpretability with SHAP.

---

### 3. Single-Cell RNA-Seq Clustering & Classification  
**Notebook:** `SingleCellRNASeq.ipynb`  
**Goal:** Cluster and predict immune cell types from single-cell data.  
**Unsupervised:** PCA + Leiden, K-Means, Hierarchical  
**Supervised:** Logistic Regression, Random Forest, MLP Neural Network  
**Focus:** Dimensionality reduction, marker identification, supervised label transfer.

---

### 4. Transcription Factor Binding Site Prediction  
**Notebook:** `TFBindingSitePrediction.ipynb`  
**Goal:** Predict TF binding sites from DNA sequences.  
**Model:** CNN (PyTorch)  
**Focus:** Sequence encoding, CNN design, motif-level interpretation.

---

### 5. Predicting Breast Tumor Malignancy with Deep Convolutional Models
**Notebook:** `BreastTumorMalignancyCNN.ipynb`  
**Goal:** Predict breast tumor malignancy from histopathology images using deep CNN architectures.  
**Model:** Custom PyTorch CNN, Fine-tuned ResNet18, FiLM-augmented ResNet18  
**Focus:** Transfer learning, fine-tuning, conditional modulation, and robust evaluation with class imbalance handling.
