# 📊 Vertical Federated Learning for Cardiovascular Disease Prediction

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Federated Learning](https://img.shields.io/badge/Federated_Learning-Vertical-red.svg)
![Privacy](https://img.shields.io/badge/Privacy-DP_&_SMPC-purple.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)
![MSc](https://img.shields.io/badge/MSc-Final_Year_Project-orange.svg)

</div>

## 🎓 MSc Final Year Project

This repository implements a comprehensive **Vertical Federated Learning (VFL)** framework for cardiovascular disease prediction, incorporating advanced privacy-preserving techniques including **Differential Privacy (DP)** and **Secure Multi-Party Computation (SMPC)**.

---

## 🔬 Overview

Cardiovascular diseases (CVDs) remain the leading cause of death globally, accounting for approximately 17.9 million deaths annually. Healthcare institutions possess valuable patient data but cannot share it due to strict privacy regulations (HIPAA, GDPR, and local healthcare data protection laws). This project addresses this critical challenge using **Vertical Federated Learning (VFL)** , enabling collaborative model training across multiple institutions without any raw data exchange.

### The Problem

- ❌ **Data Silos**: Patient data is scattered across different hospitals and healthcare providers
- ❌ **Privacy Regulations**: Strict laws prevent sharing of sensitive medical information
- ❌ **Limited Data**: Single-institution models have insufficient data diversity
- ❌ **Feature Gap**: Different hospitals collect different types of patient information

### Our Solution

- ✅ **Collaborative Learning**: Train models across institutions without data sharing
- ✅ **Multiple Privacy Mechanisms**: Choose between DP, SMPC, or hybrid approaches
- ✅ **Improved Accuracy**: Leverage diverse features from multiple sources
- ✅ **Regulatory Compliance**: Built-in privacy guarantees satisfy legal requirements

### Four Implementation Approaches

| Approach | Description | Privacy Level | Computational Cost | Use Case |
|----------|-------------|---------------|-------------------|----------|
| **Standard VFL** | Baseline federated learning without privacy | Low | Low | Performance baseline |
| **VFL + DP** | Local Differential Privacy with Gaussian noise | High | Medium | Strict privacy requirements |
| **VFL + SMPC** | Secure Multi-Party Computation with secret sharing | Very High | High | Maximum security needed |
| **VFL + DT + DP** | Decision Trees with Differential Privacy | High | Medium | Interpretable models needed |

---

## ✨ Key Features

### Core Federated Learning Features
- ✅ **Vertical Federated Learning** implementation with Logistic Regression
- ✅ **Multi-Client Architecture** supporting 4 healthcare institutions
- ✅ **Real Dataset Integration** from multiple cardiovascular disease sources
- ✅ **Automatic Feature Alignment** across clients with padding
- ✅ **Client Adjustment Phase** with optimal line search

### Privacy-Preserving Features
- 🔒 **Differential Privacy (DP)** with configurable epsilon budgets
- 🔒 **Local DP** where noise is added at client level before sharing
- 🔒 **Secure Multi-Party Computation (SMPC)** using additive secret sharing (3 shares)
- 🔒 **Gaussian Mechanism** for DP implementation
- 🔒 **Gradient Clipping** to bound sensitivity (configurable threshold)
- 🔒 **Information Gain Perturbation** for decision tree privacy

### Monitoring & Reporting Features
- 📊 **Comprehensive Metrics** (Accuracy, Precision, Recall, F1 Score)
- 📈 **Real-time Visualization** of performance over training rounds
- 📉 **Confusion Matrices** for each client at each round
- ⏱️ **Detailed Timing Analysis** per component and per client
- 📄 **Automated Report Generation** (Word documents with embedded plots)
- 📊 **Progress Tracking** with early stopping mechanism

### Technical Features
- 🔄 **Early Stopping** with configurable patience (default: 3 rounds)
- 🎯 **Line Search Algorithm** for optimal model interpolation (0 to 1, 11 steps)
- 🌳 **Custom Decision Tree Implementation** with information gain splitting
- 🔢 **Modular Arithmetic** for SMPC using Mersenne prime (2³¹ - 1)
- 📦 **Modular Code Design** with reusable functions
- 🎨 **Seaborn Visualizations** with publication-quality styling

---


---

## 🛠 Technologies Used

### Core Technologies
| Technology | Version | Purpose |
|------------|---------|---------|
| **Python** | 3.10+ | Core programming language |
| **scikit-learn** | 1.0+ | Machine learning models & evaluation metrics |
| **NumPy** | 1.21+ | Numerical computations & random number generation |
| **Pandas** | 1.3+ | Data manipulation and preprocessing |

### Visualization & Reporting
| Technology | Version | Purpose |
|------------|---------|---------|
| **Matplotlib** | 3.4+ | Basic data visualization |
| **Seaborn** | 0.11+ | Statistical visualizations and heatmaps |
| **python-docx** | 0.8.11+ | Automated Microsoft Word report generation |

### Development Tools
| Tool | Purpose |
|------|---------|
| **Jupyter Notebook** | Interactive development and experimentation |
| **Git** | Version control |
| **GitHub** | Repository hosting |



