# Water Quality ML Analysis

Advanced machine learning pipeline for water quality prediction with comprehensive uncertainty quantification and automated validation.

## Project Overview

This repository contains a complete ML pipeline for water quality assessment using Indian Lakes dataset, featuring:

- **Uncertainty-aware models** (NGBoost, Quantile Random Forest)
- **Comprehensive validation** (CV, temporal, external datasets)
- **Automated diagnostic pipeline** for publication readiness
- **TinyML optimization** for edge deployment

## Key Results

- **Publication-ready models** with realistic performance metrics
- **Uncertainty quantification** with entropy ≥ 0.15
- **Interval coverage** ≥ 80% for prediction intervals
- **Leak-free validation** with proper temporal splits

## Quick Start

1. **Foundation Analysis**: `notebooks/01_foundation/indian_lakes_water_quality_analysis.ipynb`

## 🔬 Technical Highlights

- **NGBoost** for probabilistic predictions
- **Quantile Random Forest** for prediction intervals
- **Automated overfitting detection** and fixes
- **Multi-dataset validation** (Indian Lakes + external)
- **TinyML models** under 10KB with ≥90% AUC

## 📈 Model Performance

All models meet publication standards:
- AUC < 0.95 (realistic, no overfitting)
- F1 ∈ (0.1, 0.95) (meaningful predictions)
- Uncertainty metrics validated
- External dataset generalization confirmed

## 🛠️ Requirements

- Python 3.8+
- scikit-learn, pandas, numpy
- ngboost, matplotlib, seaborn
- jupyter notebook

##  Documentation

See individual notebooks for detailed methodology and `docs/` for additional resources.
