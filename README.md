## 1. Project Overview
This project presents a systematic benchmarking of multiple machine learning classifiers—**Multinomial Logistic Regression (MLR)**, **Support Vector Machines (SVM)**, and **Multi-layer Perceptron (MLP)**. [cite_start]The study evaluates performance across three distinct data scales: structured wine data, mid-scale facial images, and large-scale high-dimensional facial features. 

## 2. Experimental Design & Datasets
* [cite_start]**ds0 (Wine Dataset)**: Focused on hyperparameter sensitivity in structured data. [cite: 1365-1369, 1378-1379]
* [cite_start]**ds1 (Yale Face Dataset)**: Investigated the impact of **Gaussian Denoising** on image classification. [cite: 1519-1522, 2061-2065]
* [cite_start]**ds2 (AllFaces Dataset)**: Challenged classifiers with high-dimensional feature spaces (32,256 features, 38 classes) using **PCA-based dimensionality reduction**. [cite: 2133-2136, 2403-2405]

## 3. Key Technical Implementations
* [cite_start]**Hyperparameter Tuning**: Utilized **GridSearchCV** and **LogisticRegressionCV** for automated parameter optimization. [cite: 1310-1329, 1411-1413]
* [cite_start]**Diagnostic Tools**: Analyzed **Learning Curves** to evaluate bias-variance tradeoffs and **Normalized Confusion Matrices** for error distribution analysis. [cite: 249, 1353-1364, 1560-1587]
* [cite_start]**Preprocessing**: Implemented **StandardScaler**, **PCA/SVD** (up to 0.95 variance explained), and **Gaussian Blur** filtering. [cite: 1404-1410, 1502-1512, 2169-2173]
