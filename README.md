## 1. Project Overview
This project presents a systematic benchmarking of multiple machine learning classifiers—**Multinomial Logistic Regression (MLR)**, **Support Vector Machines (SVM)**, and **Multi-layer Perceptron (MLP)**. The study evaluates performance across three distinct data scales: structured wine data, mid-scale facial images, and large-scale high-dimensional facial features. 

## 2. Experimental Design & Datasets
* **ds0 (Wine Dataset)**: Focused on hyperparameter sensitivity in structured data. 
* **ds1 (Yale Face Dataset)**: Investigated the impact of **Gaussian Denoising** on image classification. 
* **ds2 (AllFaces Dataset)**: Challenged classifiers with high-dimensional feature spaces (32,256 features, 38 classes) using **PCA-based dimensionality reduction**. 

## 3. Key Technical Implementations
* **Hyperparameter Tuning**: Utilized **GridSearchCV** and **LogisticRegressionCV** for automated parameter optimization. 
* **Diagnostic Tools**: Analyzed **Learning Curves** to evaluate bias-variance tradeoffs and **Normalized Confusion Matrices** for error distribution analysis. 
* **Preprocessing**: Implemented **StandardScaler**, **PCA/SVD** (up to 0.95 variance explained), and **Gaussian Blur** filtering. 
