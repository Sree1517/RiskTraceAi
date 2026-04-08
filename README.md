# RiskShift AI v5.1 - Multi-Modal CVD Risk Prediction

[![Model AUC](https://img.shields.io/badge/AUC-0.92-blue.svg)](https://github.com/venky-1710/riskshift-ai) [![Datasets](https://img.shields.io/badge/Datasets-6-green.svg)](https://github.com/venky-1710/riskshift-ai) [![Features](https://img.shields.io/badge/Features-24-orange.svg)](https://github.com/venky-1710/riskshift-ai)

**RiskShift AI v5.1** fuses **6 clinical datasets** (Cardio, Heart, Failure, ECG, Stress, Genetics) into a production-ready **XGBoost model** predicting cardiovascular disease risk with **92% AUC**. Covers **all 11 WHO risk factors** with **LIME/SHAP explainability**, patient simulator, and deployment-ready `.pkl` exports.

## 🚀 Quick Start (One-Click Demo)

```bash
git clone https://github.com/venky-1710/riskshift-ai.git
cd riskshift-ai
pip install -r requirements.txt
jupyter notebook RiskShift_AI_v5.1.ipynb
```

**Zero configuration** - auto-detects CSVs, pulls stress data live from GitHub, generates synthetic genetics fallback.

## 🌟 Features

| Feature | Status |
|---------|--------|
| **6-Dataset Fusion** | ✅ Cardio+Heart+Failure+ECG+Stress+Genetics (70K+ patients) |
| **11 WHO Risk Factors** | ✅ Cholesterol, BP, Genetics, Smoking, Diabetes, Diet, BMI, Inactivity, Alcohol, Stress, Med Gap |
| **24 ML Features** | ✅ Plaque risk, acute triggers, HRV proxy, polygenic scores |
| **92% AUC Performance** | ✅ XGBoost + 5-fold CV validation |
| **Explainable AI** | ✅ LIME (patient) + SHAP (population) |
| **Patient Simulator** | ✅ Real-time "what-if" scenarios |
| **Production Export** | ✅ `.pkl` files for FastAPI/Streamlit |

## 📊 Performance Metrics
