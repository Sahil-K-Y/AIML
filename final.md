# Production-Grade AI/ML Engineer Master Roadmap — Detailed Day-by-Day Version

**Timeline:** 1 June 2026 to 31 December 2026  
**Daily Commitment:** 3–4 hours/day  
**Primary Stack:** Python, Scikit-Learn, PyTorch, FastAPI, React, Docker, MLflow, TailwindCSS  
**Execution Formula:** Concept → Practice → Deliverable  
**Explicitly Skipped:** SQL, Git workflow, DSA, RL, Kubernetes, Feast, BentoML, heavy generative image topics

---

## How to Use This Roadmap

Each day should roughly follow this structure:
- **45–60 min:** Learn the concept
- **90–120 min:** Practice by coding
- **45–60 min:** Finish one concrete deliverable

For project days, prefer:
- clean folder structure
- reusable functions
- logging where useful
- tests where relevant
- short README notes
- saved artifacts/screenshots

---

# PHASE 1 — EDA & FEATURE ENGINEERING MASTERY

**01 Jun 2026 to 16 Jun 2026**  
**Status:** Completed

### 01 Jun — Day 001 — Python Environment Setup
**Concept:** Virtual environments, pip installation, Jupyter/VS Code flow, verifying packages, reading CSV files.  
**Practice:** Create a clean environment, install numpy, pandas, matplotlib, seaborn, scikit-learn, jupyter; open notebook; load sample CSV.  
**Deliverable:** `Phase-1/Day 01 - Environment Setup.ipynb` with package verification and sample dataset load.

### 02 Jun — Day 002 — NumPy Foundations
**Concept:** Arrays, dimensions, shape, dtype, slicing, indexing, broadcasting, reshaping.  
**Practice:** Write 20 array operations including addition, multiplication, transpose, reshape, boolean masking, row/column extraction.  
**Deliverable:** `Phase-1/Day 02 - NumPy Foundations.ipynb` containing solved array tasks.

### 03 Jun — Day 003 — pandas Core DataFrames
**Concept:** Series vs DataFrame, indexing, filtering, sorting, selecting columns, value counts, grouping.  
**Practice:** Load a messy CSV and perform selection, filtering, sorting, basic aggregation, renaming, type conversion.  
**Deliverable:** `Phase-1/Day 03 - pandas Core.ipynb` with a mini data-cleaning walkthrough.

### 04 Jun — Day 004 — Data Preprocessing & Cleaning
**Concept:** Missing values, duplicates, type formatting, whitespace cleanup, category standardization.  
**Practice:** Build helper functions for filling numeric nulls, standardizing text labels, removing duplicates.  
**Deliverable:** `Phase-1/Day 04 - Data Cleaning.ipynb` with reusable cleaning cells.

### 05 Jun — Day 005 — Outlier Detection
**Concept:** IQR, quartiles, lower and upper fences, Z-score idea, anomaly intuition.  
**Practice:** Implement IQR and Z-score outlier detection from scratch and compare results on numeric columns.  
**Deliverable:** `Phase-1/Day 05 - Outlier Detection.ipynb` with plots and flagged rows.

### 06 Jun — Day 006 — Descriptive Statistics & Univariate Analysis
**Concept:** Mean, median, mode, variance, std deviation, skewness, kurtosis, histograms, boxplots.  
**Practice:** Compute summary stats and visualize distributions for all major columns in a dataset.  
**Deliverable:** `Phase-1/Day 06 - Univariate Analysis.ipynb`.

### 07 Jun — Day 007 — Bivariate Analysis
**Concept:** Correlation, covariance, pairwise relationships, scatter plots, grouped comparisons.  
**Practice:** Build correlation matrix, scatter plots, category vs target plots, and identify strongest relationships.  
**Deliverable:** `Phase-1/Day 07 - Bivariate Analysis.ipynb`.

### 08 Jun — Day 008 — Multivariate Analysis
**Concept:** Pairplots, heatmaps, crosstabs, pivot tables, grouped feature interactions.  
**Practice:** Explore interactions across 3+ variables and compare subgroup patterns.  
**Deliverable:** `Phase-1/Day 08 - Multivariate Analysis.ipynb`.

### 09 Jun — Day 009 — Data Cleaning Pipeline
**Concept:** Turning one-off cleaning into a repeatable workflow.  
**Practice:** Chain missing value handling, duplicate removal, and type corrections into a step-by-step pipeline.  
**Deliverable:** `Phase-1/Day 09 - Cleaning Pipeline.ipynb`.

### 10 Jun — Day 010 — EDA Capstone Titanic
**Concept:** Full EDA flow on a real tabular problem.  
**Practice:** Analyze Titanic dataset end to end: nulls, target balance, distributions, relationships, survival insights.  
**Deliverable:** `Phase-1/Day 10 - Titanic EDA Capstone.ipynb`.

### 11 Jun — Day 011 — Feature Encoding
**Concept:** Nominal vs ordinal categories, one-hot encoding, label encoding, target encoding intuition.  
**Practice:** Encode multiple categorical columns using appropriate encoders and compare resulting feature matrices.  
**Deliverable:** `Phase-1/Day 11 - Feature Encoding.ipynb`.

### 12 Jun — Day 012 — Feature Scaling
**Concept:** Standardization vs normalization, scaling-sensitive models, feature magnitude effects.  
**Practice:** Apply StandardScaler and MinMaxScaler to the same numeric data and compare distributions.  
**Deliverable:** `Phase-1/Day 12 - Feature Scaling.ipynb`.

### 13 Jun — Day 013 — Handling Skewed Data
**Concept:** Why skew matters, log transform, Box-Cox, Yeo-Johnson, normalization effect.  
**Practice:** Transform skewed columns and compare before/after histograms and skew metrics.  
**Deliverable:** `Phase-1/Day 13 - Skew Handling.ipynb`.

### 14 Jun — Day 014 — Feature Creation
**Concept:** Ratio features, interaction features, polynomial features, domain-based features.  
**Practice:** Engineer at least 5 new features and justify why each may help the model.  
**Deliverable:** `Phase-1/Day 14 - Feature Creation.ipynb`.

### 15 Jun — Day 015 — Train-Test Split & Cross-Validation
**Concept:** Holdout validation, stratified split, K-Fold, data leakage during split.  
**Practice:** Split data properly and run StratifiedKFold for a classification dataset.  
**Deliverable:** `Phase-1/Day 15 - Split and CV.ipynb`.

### 16 Jun — Day 016 — Feature Engineering Capstone
**Concept:** Combining encoding, scaling, skew handling, and feature creation into one workflow.  
**Practice:** Build a reproducible preprocessing sequence for a tabular dataset.  
**Deliverable:** `Phase-1/Day 16 - Feature Engineering Capstone.ipynb`.

---

# PHASE 2 — REGRESSION FOUNDATIONS & FIRST APP

**17 Jun 2026 to 30 Jun 2026**

### 17 Jun — Day 017 — Simple Linear Regression Intuition
**Concept:** Best fit line, slope, intercept, residuals, RSS, OLS intuition.  
**Practice:** Work through small numerical examples by hand and verify with Python.  
**Deliverable:** `Phase-2/Day 17 - Linear Regression Intuition.md`.

### 18 Jun — Day 018 — Cost Function MSE
**Concept:** Mean Squared Error, loss surface, error minimization intuition.  
**Practice:** Compute MSE manually over different parameter values and visualize error changes.  
**Deliverable:** `Phase-2/Day 18 - MSE.ipynb`.

### 19 Jun — Day 019 — Gradient Descent
**Concept:** Gradient updates, learning rate, convergence, overshooting, local behavior.  
**Practice:** Implement gradient descent for simple linear regression from scratch and plot parameter updates.  
**Deliverable:** `Phase-2/Day 19 - Gradient Descent.ipynb`.

### 20 Jun — Day 020 — Linear Regression in Scikit-Learn
**Concept:** Estimator API, fit, predict, coefficients, intercept extraction.  
**Practice:** Train a LinearRegression model and compare predictions against synthetic truth.  
**Deliverable:** `Phase-2/Day 20 - Linear Regression Implementation.ipynb`.

### 21 Jun — Day 021 — Regression Evaluation
**Concept:** RMSE, MAE, R2, adjusted R2, interpretation of model errors.  
**Practice:** Evaluate 2–3 regression models on same dataset and compare metrics.  
**Deliverable:** `Phase-2/Day 21 - Evaluation Metrics.ipynb`.

### 22 Jun — Day 022 — Multiple Linear Regression
**Concept:** Multi-feature regression, coefficient interpretation, multicollinearity intuition.  
**Practice:** Train on multi-column dataset and inspect feature weights.  
**Deliverable:** `Phase-2/Day 22 - Multiple Regression.ipynb`.

### 23 Jun — Day 023 — Polynomial Regression
**Concept:** Nonlinear relationships through transformed features, underfitting vs overfitting.  
**Practice:** Fit polynomial models of multiple degrees and compare train/validation scores.  
**Deliverable:** `Phase-2/Day 23 - Polynomial Regression.ipynb`.

### 24 Jun — Day 024 — Ridge & Lasso Regression
**Concept:** Regularization, shrinkage, feature selection effect of L1.  
**Practice:** Train Ridge and Lasso over different alpha values; compare coefficients.  
**Deliverable:** `Phase-2/Day 24 - Ridge Lasso.ipynb`.

### 25 Jun — Day 025 — Elastic Net Regression
**Concept:** Combined penalty, L1 ratio, tuning regularized models.  
**Practice:** Fit ElasticNet and compare against Ridge/Lasso baseline.  
**Deliverable:** `Phase-2/Day 25 - Elastic Net.ipynb`.

### 26 Jun — Day 026 — SGD Regressor
**Concept:** Online-style learning, incremental optimization, scaling importance.  
**Practice:** Train SGDRegressor on scaled data and inspect performance differences.  
**Deliverable:** `Phase-2/Day 26 - SGD Regressor.ipynb`.

### 27 Jun — Day 027 — Mini Regression App Planning
**Concept:** Turning a model into a small interactive product.  
**Practice:** Decide app inputs, target output, validation logic, and file structure.  
**Deliverable:** `Phase-2/Day 27 - App Planning.md`.

### 28 Jun — Day 028 — Model Packaging Basics
**Concept:** joblib/pickle usage, preprocessing consistency, inference script structure.  
**Practice:** Save trained model and write a separate script to load and predict.  
**Deliverable:** `Phase-2/artifacts/model.joblib` + `Phase-2/src/predict.py`.

### 29 Jun — Day 029 — Simple UI Integration
**Concept:** Lightweight UI for inference.  
**Practice:** Build a small Streamlit or Python-based prediction form for the regression model.  
**Deliverable:** `Phase-2/app.py`.

### 30 Jun — Day 030 — Regression Mini Project Polish
**Concept:** Moving from notebook work to repo-quality output.  
**Practice:** Organize notebook, app, artifacts, screenshots, and README.  
**Deliverable:** `Phase-2/README.md` + cleaned mini project folder.

---

# PHASE 3 — LOGISTIC REGRESSION & CLASSIFICATION FOUNDATIONS

**01 Jul 2026 to 14 Jul 2026**

### 01 Jul — Day 031 — Titanic Pipeline Architecture with Logging
**Concept:** Binary classification workflow, project structure, Python logging.  
**Practice:** Build preprocessing functions and replace print statements with logger calls.  
**Deliverable:** `Phase-3/src/pipeline.py` with logging.

### 02 Jul — Day 032 — Pipeline Verification with Pytest
**Concept:** Unit tests for preprocessing code and shape stability.  
**Practice:** Write tests for null handling, output dimension stability, and datatype expectations.  
**Deliverable:** `Phase-3/tests/test_pipeline.py`.

### 03 Jul — Day 033 — Sigmoid, Odds, Log-Odds
**Concept:** Logistic intuition, sigmoid mapping, odds ratio, logit interpretation.  
**Practice:** Implement sigmoid and visualize probability outputs across a range of z values.  
**Deliverable:** `Phase-3/Day 33 - Sigmoid.ipynb`.

### 04 Jul — Day 034 — Logistic Regression Implementation
**Concept:** Classifier fit/predict flow, probability scores, coefficient interpretation.  
**Practice:** Train logistic regression on Titanic or another binary dataset and inspect predictions.  
**Deliverable:** `Phase-3/Day 34 - Logistic Regression.ipynb`.

### 05 Jul — Day 035 — Log Loss and MLE Intuition
**Concept:** Cross-entropy/log-loss, likelihood maximization, penalty for confident wrong predictions.  
**Practice:** Compute log-loss manually and validate using scikit-learn.  
**Deliverable:** `Phase-3/Day 35 - Log Loss.ipynb`.

### 06 Jul — Day 036 — Multiclass Logistic Regression & Softmax
**Concept:** OvR, multinomial classification, softmax output probabilities.  
**Practice:** Train a multiclass logistic regression model on iris or wine dataset.  
**Deliverable:** `Phase-3/Day 36 - Softmax.ipynb`.

### 07 Jul — Day 037 — Confusion Matrix & Core Metrics
**Concept:** Accuracy, precision, recall, F1, type I/II error intuition.  
**Practice:** Build evaluation metrics from scratch and compare against sklearn outputs.  
**Deliverable:** `Phase-3/Day 37 - Metrics.ipynb`.

### 08 Jul — Day 038 — ROC-AUC and PR-AUC
**Concept:** Threshold tradeoffs, TPR/FPR, imbalanced metric behavior.  
**Practice:** Plot ROC and PR curves and explain when each is useful.  
**Deliverable:** `Phase-3/Day 38 - ROC PR.ipynb`.

### 09 Jul — Day 039 — Threshold Tuning & Imbalance Basics
**Concept:** Decision threshold adjustment, F1 optimization, class_weight intuition.  
**Practice:** Tune threshold and compare performance at multiple cutoffs.  
**Deliverable:** `Phase-3/Day 39 - Threshold Tuning.ipynb`.

### 10 Jul — Day 040 — Stratified Validation for Classification
**Concept:** Stratified split, K-Fold for classification, avoiding target imbalance distortions.  
**Practice:** Train using StratifiedKFold and report averaged metrics.  
**Deliverable:** `Phase-3/Day 40 - Stratified CV.ipynb`.

### 11 Jul — Day 041 — Data Leakage & sklearn Pipelines
**Concept:** Target leakage, preprocessing leakage, safe fit/transform boundaries.  
**Practice:** Build a `Pipeline` + `ColumnTransformer` workflow that avoids leakage.  
**Deliverable:** `Phase-3/Day 41 - Leakage Free Pipeline.ipynb`.

### 12 Jul — Day 042 — Regularization in Logistic Regression
**Concept:** L1 vs L2 in classification, C parameter, coefficient sparsity.  
**Practice:** Train regularized logistic models and compare feature coefficients.  
**Deliverable:** `Phase-3/Day 42 - LR Regularization.ipynb`.

### 13 Jul — Day 043 — Titanic Finalization
**Concept:** Packaging a complete classification project.  
**Practice:** Save pipeline, generate plots, create summary, export model artifact.  
**Deliverable:** `Phase-3/README.md`, saved model, final notebook.

### 14 Jul — Day 044 — Phase 3 Review & Interview Drill
**Concept:** Review and retention.  
**Practice:** Answer 10 conceptual classification questions and clean code style.  
**Deliverable:** `Phase-3/Day 44 - Review.md`.

---

# PHASE 4 — ADVANCED PREPROCESSING + CORE CLASSIFIERS

**15 Jul 2026 to 05 Aug 2026**

### 15 Jul — Day 045 — Missingness Taxonomy
**Concept:** MCAR, MAR, MNAR, null pattern bias.  
**Practice:** Profile missingness across a real dataset and identify likely missingness types.  
**Deliverable:** `Phase-4/Day 45 - Missingness.ipynb`.

### 16 Jul — Day 046 — Advanced Imputation Techniques
**Concept:** SimpleImputer vs KNNImputer vs IterativeImputer.  
**Practice:** Compare imputation strategies on same dataset and inspect downstream score effect.  
**Deliverable:** `Phase-4/Day 46 - Imputation.ipynb`.

### 17 Jul — Day 047 — Safe Encoding & Leakage Prevention
**Concept:** High-cardinality encoding and leakage control.  
**Practice:** Implement encoding inside CV-safe pipeline.  
**Deliverable:** `Phase-4/Day 47 - Safe Encoding.ipynb`.

### 18 Jul — Day 048 — Feature Creation Mechanics
**Concept:** Interaction terms, bins, ratios, power transforms.  
**Practice:** Generate advanced features and justify their usefulness.  
**Deliverable:** `Phase-4/Day 48 - Feature Creation.ipynb`.

### 19 Jul — Day 049 — Feature Selection Methods
**Concept:** Filter, wrapper, embedded feature selection.  
**Practice:** Compare SelectKBest, RFE, and Lasso-based selection.  
**Deliverable:** `Phase-4/Day 49 - Feature Selection.ipynb`.

### 20 Jul — Day 050 — Outlier Detection Deep Dive
**Concept:** IQR, Z-score, Isolation Forest basics.  
**Practice:** Compare rule-based and model-based outlier detection.  
**Deliverable:** `Phase-4/Day 50 - Outliers.ipynb`.

### 21 Jul — Day 051 — Outlier Handling with Custom Transformers
**Concept:** Capping, winsorization, custom sklearn transformers.  
**Practice:** Build a custom transformer that clips numeric columns.  
**Deliverable:** `Phase-4/Day 51 - Custom Outlier Transformer.ipynb`.

### 22 Jul — Day 052 — Date & Text Feature Engineering
**Concept:** Extracting day, month, weekday, cyclic features, text length/count features.  
**Practice:** Engineer date and text metadata features.  
**Deliverable:** `Phase-4/Day 52 - Date Text Features.ipynb`.

### 23 Jul — Day 053 — House Prices Project Part 1
**Concept:** Project framing and preprocessing setup for regression.  
**Practice:** Build baseline cleaning and preprocessing pipeline for House Prices dataset.  
**Deliverable:** `Phase-4/Day 53 - House Prices Part 1.ipynb`.

### 24 Jul — Day 054 — House Prices Project Part 2
**Concept:** Feature engineering and baseline modeling.  
**Practice:** Add engineered features and train 2–3 regression baselines.  
**Deliverable:** `Phase-4/Day 54 - House Prices Part 2.ipynb`.

### 25 Jul — Day 055 — KNN Theory
**Concept:** Distance metrics, neighborhood intuition, scaling effect.  
**Practice:** Compute distances manually and understand K choice.  
**Deliverable:** `Phase-4/Day 55 - KNN Theory.ipynb`.

### 26 Jul — Day 056 — KNN Practical & Tuning
**Concept:** Scaled pipelines, tuning K, weighted neighbors.  
**Practice:** Build KNN pipeline and compare multiple K values.  
**Deliverable:** `Phase-4/Day 56 - KNN Practical.ipynb`.

### 27 Jul — Day 057 — Naive Bayes Classifiers
**Concept:** Bayes theorem, Gaussian NB, Multinomial NB intuition.  
**Practice:** Train Gaussian NB on numeric data and compare with LR baseline.  
**Deliverable:** `Phase-4/Day 57 - Naive Bayes.ipynb`.

### 28 Jul — Day 058 — Multi-class Evaluation Deep Dive
**Concept:** Macro, micro, weighted metrics and multiclass confusion matrix.  
**Practice:** Evaluate a multiclass classifier using all averaging strategies.  
**Deliverable:** `Phase-4/Day 58 - Multiclass Eval.ipynb`.

### 29 Jul — Day 059 — Bias-Variance Tradeoff
**Concept:** Underfitting vs overfitting, error decomposition intuition.  
**Practice:** Plot train vs validation performance over model complexity.  
**Deliverable:** `Phase-4/Day 59 - Bias Variance.ipynb`.

### 30 Jul — Day 060 — Learning Curves
**Concept:** Diagnosing data limitations and model behavior with sample growth.  
**Practice:** Generate learning curves for classification or regression pipeline.  
**Deliverable:** `Phase-4/Day 60 - Learning Curves.ipynb`.

### 31 Jul — Day 061 — Heart Disease Project Part 1
**Concept:** Binary classification project setup and EDA.  
**Practice:** Explore class balance, data quality, and baseline preprocessing.  
**Deliverable:** `Phase-4/Day 61 - Heart Disease Part 1.ipynb`.

### 01 Aug — Day 062 — Heart Disease Project Part 2
**Concept:** Baseline classification modeling.  
**Practice:** Train logistic regression and KNN pipelines and compare results.  
**Deliverable:** `Phase-4/Day 62 - Heart Disease Part 2.ipynb`.

### 02 Aug — Day 063 — Heart Disease Project Part 3
**Concept:** Tuning and project summarization.  
**Practice:** Tune model, create ROC/PR plots, save best pipeline.  
**Deliverable:** `Phase-4/Day 63 - Heart Disease Final.ipynb`.

### 03 Aug — Day 064 — Imbalanced Learning with SMOTE vs Class Weights
**Concept:** Oversampling vs cost-sensitive learning.  
**Practice:** Compare SMOTE and `class_weight` impact on metrics.  
**Deliverable:** `Phase-4/Day 64 - Imbalance Handling.ipynb`.

### 04 Aug — Day 065 — Clustering Overview: K-Means + PCA
**Concept:** Unsupervised intuition, K-Means basics, PCA dimensionality reduction.  
**Practice:** Run PCA + K-Means on simple dataset and interpret clusters.  
**Deliverable:** `Phase-4/Day 65 - PCA KMeans.ipynb`.

### 05 Aug — Day 066 — Phase 4 Review & Portfolio Sync
**Concept:** Consolidation and cleanup.  
**Practice:** Refactor House Prices and Heart Disease folders into cleaner project layouts.  
**Deliverable:** `Phase-4/Day 66 - Sync.md`.

---

# PHASE 5 — TREES, ENSEMBLES, BOOSTING, SVM

**06 Aug 2026 to 29 Aug 2026**

### 06 Aug — Day 067 — Decision Tree Theory
**Concept:** Entropy, Gini, information gain, recursive splitting.  
**Practice:** Compute impurity measures manually on toy data.  
**Deliverable:** `Phase-5/Day 67 - Tree Theory.ipynb`.

### 07 Aug — Day 068 — Decision Tree Practical
**Concept:** Fitting, visualization, overfitting controls.  
**Practice:** Train classifier and vary `max_depth`, `min_samples_split`.  
**Deliverable:** `Phase-5/Day 68 - Tree Practical.ipynb`.

### 08 Aug — Day 069 — Random Forest Theory
**Concept:** Bagging, bootstrap sampling, feature randomness, OOB intuition.  
**Practice:** Simulate voting behavior across multiple trees.  
**Deliverable:** `Phase-5/Day 69 - RF Theory.ipynb`.

### 09 Aug — Day 070 — Random Forest Practical
**Concept:** Ensemble training and feature importance.  
**Practice:** Train RandomForestClassifier and inspect top features.  
**Deliverable:** `Phase-5/Day 70 - RF Practical.ipynb`.

### 10 Aug — Day 071 — Random Forest Tuning
**Concept:** Hyperparameter search and validation.  
**Practice:** Run GridSearchCV or RandomizedSearchCV on RF pipeline.  
**Deliverable:** `Phase-5/Day 71 - RF Tuning.ipynb`.

### 11 Aug — Day 072 — Boosting Theory
**Concept:** Weak learners, residual fitting, additive modeling.  
**Practice:** Understand boosting step by step on toy examples.  
**Deliverable:** `Phase-5/Day 72 - Boosting Theory.ipynb`.

### 12 Aug — Day 073 — XGBoost Fundamentals
**Concept:** Gradient boosting workflow, regularization, tree boosting in practice.  
**Practice:** Train XGBoost model on structured dataset and compare with RF.  
**Deliverable:** `Phase-5/Day 73 - XGBoost.ipynb`.

### 13 Aug — Day 074 — LightGBM & CatBoost Overview
**Concept:** Faster boosting variants, handling categorical features, speed/performance tradeoff.  
**Practice:** Compare LightGBM/CatBoost behavior at high level.  
**Deliverable:** `Phase-5/Day 74 - LGBM CatBoost.ipynb`.

### 14 Aug — Day 075 — Optuna Tuning Integration
**Concept:** Automated hyperparameter search and optimization studies.  
**Practice:** Run an Optuna study for XGBoost or Random Forest.  
**Deliverable:** `Phase-5/Day 75 - Optuna.ipynb`.

### 15 Aug — Day 076 — Voting & Stacking Classifiers
**Concept:** Ensemble combination strategies, meta-models.  
**Practice:** Build soft voting and stacking classifiers from base learners.  
**Deliverable:** `Phase-5/Day 76 - Ensembles.ipynb`.

### 16 Aug — Day 077 — SVM Theory
**Concept:** Margins, support vectors, kernels, regularization parameter C.  
**Practice:** Understand separable vs non-separable examples visually.  
**Deliverable:** `Phase-5/Day 77 - SVM Theory.ipynb`.

### 17 Aug — Day 078 — SVM Practical
**Concept:** Linear vs RBF kernels, gamma intuition.  
**Practice:** Train SVMs on scaled data and compare performance.  
**Deliverable:** `Phase-5/Day 78 - SVM Practical.ipynb`.

### 18 Aug — Day 079 — Model Comparison Framework
**Concept:** Benchmarking multiple classifiers under one evaluation setup.  
**Practice:** Compare LR, KNN, DT, RF, XGBoost, SVM on same dataset.  
**Deliverable:** `Phase-5/Day 79 - Benchmark.ipynb`.

### 19 Aug — Day 080 — Customer Churn Project Part 1
**Concept:** End-to-end project setup for churn prediction.  
**Practice:** Run EDA and preprocessing design.  
**Deliverable:** `Phase-5/Day 80 - Churn Part 1.ipynb`.

### 20 Aug — Day 081 — Customer Churn Project Part 2
**Concept:** Ensemble-based training and tuning.  
**Practice:** Train RF/XGBoost and run hyperparameter search.  
**Deliverable:** `Phase-5/Day 81 - Churn Part 2.ipynb`.

### 21 Aug — Day 082 — Customer Churn Project Part 3
**Concept:** Explainability and project wrapping.  
**Practice:** Add SHAP plots, save best model, summarize insights.  
**Deliverable:** `Phase-5/Day 82 - Churn Final.ipynb`.

### 22 Aug — Day 083 — Fraud Detection Project Part 1
**Concept:** Highly imbalanced classification framing.  
**Practice:** Profile fraud dataset and define precision/recall goals.  
**Deliverable:** `Phase-5/Day 83 - Fraud Part 1.ipynb`.

### 23 Aug — Day 084 — Fraud Detection Project Part 2
**Concept:** Cost-sensitive modeling and threshold optimization.  
**Practice:** Train boosted model and tune decision threshold.  
**Deliverable:** `Phase-5/Day 84 - Fraud Part 2.ipynb`.

### 24 Aug — Day 085 — Fraud Detection Project Part 3
**Concept:** Final evaluation and export.  
**Practice:** Compare importances, summarize failure modes, save pipeline.  
**Deliverable:** `Phase-5/Day 85 - Fraud Final.ipynb`.

### 25 Aug — Day 086 — Model Calibration
**Concept:** Reliability of predicted probabilities, calibration curves, Platt scaling.  
**Practice:** Calibrate one poorly calibrated model and compare curves.  
**Deliverable:** `Phase-5/Day 86 - Calibration.ipynb`.

### 26 Aug — Day 087 — ExtraTrees Classifier
**Concept:** Randomized trees and speed/variance tradeoff.  
**Practice:** Compare ExtraTrees with RF on same dataset.  
**Deliverable:** `Phase-5/Day 87 - ExtraTrees.ipynb`.

### 27 Aug — Day 088 — SHAP Explainability for Tree Models
**Concept:** Global and local model explanation.  
**Practice:** Generate SHAP summary and force plots for best tree-based project.  
**Deliverable:** `Phase-5/Day 88 - SHAP.ipynb`.

### 28 Aug — Day 089 — Classical ML Portfolio Cleanup
**Concept:** Turning completed notebooks into presentable portfolio assets.  
**Practice:** Select strongest 3 classical ML projects and improve structure/README.  
**Deliverable:** cleaned project folders + screenshots.

### 29 Aug — Day 090 — Phase 5 Review
**Concept:** Review of trees, ensembles, boosting, SVM.  
**Practice:** Write comparison notes: when to use which model and why.  
**Deliverable:** `Phase-5/Day 90 - Review.md`.

---

# PHASE 6 — FASTAPI DEPLOYMENT FOUNDATIONS

**30 Aug 2026 to 10 Sep 2026**

### 30 Aug — Day 091 — Model Serialization
**Concept:** Joblib, pickle, artifact handling, safe loading basics.  
**Practice:** Save and reload one trained pipeline cleanly.  
**Deliverable:** `Phase-6/artifacts/model.joblib`.

### 31 Aug — Day 092 — Clean ML Project Structure
**Concept:** `src/`, `artifacts/`, `notebooks/`, `tests/`, config-driven layout.  
**Practice:** Create production-style folder structure for an inference project.  
**Deliverable:** `Phase-6/project-structure.md` + folders.

### 01 Sep — Day 093 — FastAPI Basics
**Concept:** Routes, GET vs POST, request/response flow.  
**Practice:** Build hello-world and health-check endpoints.  
**Deliverable:** `Phase-6/main.py`.

### 02 Sep — Day 094 — Pydantic Schema Validation
**Concept:** Input schemas, typing, validation, required fields.  
**Practice:** Define request and response models for a prediction API.  
**Deliverable:** `Phase-6/schemas.py`.

### 03 Sep — Day 095 — Prediction Endpoint
**Concept:** Connecting serialized model to endpoint inference.  
**Practice:** Accept input JSON, convert to DataFrame, run prediction, return result.  
**Deliverable:** `Phase-6/main.py` with `/predict` route.

### 04 Sep — Day 096 — Error Handling & Robustness
**Concept:** Validation errors, HTTP exceptions, defensive coding.  
**Practice:** Add error handling for bad inputs and missing fields.  
**Deliverable:** improved `Phase-6/main.py`.

### 05 Sep — Day 097 — API Verification & Swagger Docs
**Concept:** OpenAPI docs, Swagger testing, schema inspection.  
**Practice:** Verify all endpoints through docs UI and save screenshots.  
**Deliverable:** `Phase-6/verification.md` + screenshots.

### 06 Sep — Day 098 — Architecture Design: UI vs API
**Concept:** Decoupled client-server design and inference flow.  
**Practice:** Draw architecture showing frontend, backend, model artifact, and request lifecycle.  
**Deliverable:** `Phase-6/architecture.md` or diagram file.

### 07 Sep — Day 099 — Mini API Project Part 1
**Concept:** Standalone prediction service layout.  
**Practice:** Separate routes, schemas, utils, and model loading logic.  
**Deliverable:** modular `Phase-6/src/` structure.

### 08 Sep — Day 100 — Mini API Project Part 2
**Concept:** Refactoring toward production cleanliness.  
**Practice:** Move preprocessing and prediction logic into reusable functions.  
**Deliverable:** cleaned API project.

### 09 Sep — Day 101 — Endpoint Testing with TestClient
**Concept:** API unit tests.  
**Practice:** Write tests for health and prediction endpoints using FastAPI TestClient.  
**Deliverable:** `Phase-6/tests/test_api.py`.

### 10 Sep — Day 102 — Dockerize the API
**Concept:** Containerizing a Python inference service.  
**Practice:** Write Dockerfile and test local container run.  
**Deliverable:** `Phase-6/Dockerfile`.

---

# PHASE 7 — DEEP LEARNING FOUNDATIONS WITH PYTORCH FOCUS

**11 Sep 2026 to 24 Sep 2026**

### 11 Sep — Day 103 — Deep Learning Intro
**Concept:** Neurons, weights, biases, activations, layered networks.  
**Practice:** Compute simple neuron outputs manually.  
**Deliverable:** `Phase-7/Day 103 - DL Intro.ipynb`.

### 12 Sep — Day 104 — Forward Pass from Scratch
**Concept:** Matrix multiplication through layers.  
**Practice:** Build forward pass in NumPy for a tiny neural net.  
**Deliverable:** `Phase-7/Day 104 - Forward Pass.ipynb`.

### 13 Sep — Day 105 — Loss Functions in DL
**Concept:** MSE, BCE, CCE.  
**Practice:** Compute basic loss values from prediction vectors manually.  
**Deliverable:** `Phase-7/Day 105 - Loss Functions.ipynb`.

### 14 Sep — Day 106 — Backpropagation Intuition
**Concept:** Chain rule and gradient flow.  
**Practice:** Manually derive updates for a single neuron.  
**Deliverable:** `Phase-7/Day 106 - Backpropagation.ipynb`.

### 15 Sep — Day 107 — Optimizers
**Concept:** SGD, momentum, RMSProp, Adam.  
**Practice:** Compare optimizer behavior conceptually and visually.  
**Deliverable:** `Phase-7/Day 107 - Optimizers.ipynb`.

### 16 Sep — Day 108 — Regularization in DL
**Concept:** Dropout, batch norm, early stopping, overfitting.  
**Practice:** Observe overfitting and compare regularized runs.  
**Deliverable:** `Phase-7/Day 108 - Regularization.ipynb`.

### 17 Sep — Day 109 — PyTorch Tensors
**Concept:** Tensor creation, shape operations, device basics.  
**Practice:** Recreate NumPy operations using PyTorch tensors.  
**Deliverable:** `Phase-7/Day 109 - Tensors.ipynb`.

### 18 Sep — Day 110 — Autograd and Gradients
**Concept:** Automatic differentiation and computation graphs.  
**Practice:** Track gradients for simple scalar and vector expressions.  
**Deliverable:** `Phase-7/Day 110 - Autograd.ipynb`.

### 19 Sep — Day 111 — PyTorch Modules
**Concept:** `nn.Module`, linear layers, activations, sequential patterns.  
**Practice:** Build a simple feedforward network class.  
**Deliverable:** `Phase-7/Day 111 - Modules.ipynb`.

### 20 Sep — Day 112 — PyTorch Training Loop
**Concept:** Forward, loss, backward, optimizer step, zero_grad.  
**Practice:** Write a full training loop from scratch.  
**Deliverable:** `Phase-7/Day 112 - Training Loop.ipynb`.

### 21 Sep — Day 113 — Binary Classification in PyTorch
**Concept:** DL for tabular binary classification.  
**Practice:** Train a simple ANN on a binary dataset and measure accuracy/F1.  
**Deliverable:** `Phase-7/Day 113 - Binary Classification.ipynb`.

### 22 Sep — Day 114 — ANN Project Part 1
**Concept:** Project setup and preprocessing.  
**Practice:** Prepare a churn-style tabular dataset for ANN training.  
**Deliverable:** `Phase-7/Day 114 - ANN Project Part 1.ipynb`.

### 23 Sep — Day 115 — ANN Project Part 2
**Concept:** Model training and tuning.  
**Practice:** Tune architecture depth, hidden units, lr, and batch size.  
**Deliverable:** `Phase-7/Day 115 - ANN Project Part 2.ipynb`.

### 24 Sep — Day 116 — ANN Project Part 3
**Concept:** Evaluation, export, and documentation.  
**Practice:** Save model, summarize results, compare against classical ML baseline.  
**Deliverable:** `Phase-7/Day 116 - ANN Final.ipynb` + model file.

---

# PHASE 8 — COMPUTER VISION ESSENTIALS

**25 Sep 2026 to 05 Oct 2026**

### 25 Sep — Day 117 — CNN Theory
**Concept:** Convolution, kernels, stride, padding, feature maps.  
**Practice:** Compute output dimensions manually.  
**Deliverable:** `Phase-8/Day 117 - CNN Theory.ipynb`.

### 26 Sep — Day 118 — CNN Architecture
**Concept:** Conv → ReLU → Pool → Flatten → Dense.  
**Practice:** Define a basic CNN model.  
**Deliverable:** `Phase-8/Day 118 - CNN Architecture.ipynb`.

### 27 Sep — Day 119 — Image Preprocessing
**Concept:** Resizing, normalization, channels, tensor formatting.  
**Practice:** Load and preprocess image batches.  
**Deliverable:** `Phase-8/Day 119 - Image Prep.ipynb`.

### 28 Sep — Day 120 — MNIST Digit Classifier
**Concept:** Simple image classification pipeline.  
**Practice:** Train a CNN on MNIST and evaluate performance.  
**Deliverable:** `Phase-8/Day 120 - MNIST CNN.ipynb`.

### 29 Sep — Day 121 — CNN Diagnostics
**Concept:** Error analysis and misclassification inspection.  
**Practice:** Identify common wrong predictions and plot examples.  
**Deliverable:** `Phase-8/Day 121 - Diagnostics.ipynb`.

### 30 Sep — Day 122 — Data Augmentation
**Concept:** Generalization through transformation.  
**Practice:** Add rotation, flip, zoom, shift augmentation and compare performance.  
**Deliverable:** `Phase-8/Day 122 - Augmentation.ipynb`.

### 01 Oct — Day 123 — Transfer Learning
**Concept:** Pretrained backbones, freezing layers, fine-tuning.  
**Practice:** Use MobileNet or ResNet as frozen feature extractor.  
**Deliverable:** `Phase-8/Day 123 - Transfer Learning.ipynb`.

### 02 Oct — Day 124 — CV Project Part 1
**Concept:** Dataset preparation and split design.  
**Practice:** Organize data folders and preprocessing for one image classification problem.  
**Deliverable:** `Phase-8/Day 124 - CV Project Part 1.ipynb`.

### 03 Oct — Day 125 — CV Project Part 2
**Concept:** Model training and tuning.  
**Practice:** Train transfer learning model and track train/val curves.  
**Deliverable:** `Phase-8/Day 125 - CV Project Part 2.ipynb`.

### 04 Oct — Day 126 — CV Project Part 3
**Concept:** Final evaluation and export.  
**Practice:** Save best model and create concise project summary.  
**Deliverable:** `Phase-8/Day 126 - CV Project Final.ipynb`.

### 05 Oct — Day 127 — Grad-CAM Basics
**Concept:** Visual explanation of CNN focus regions.  
**Practice:** Generate Grad-CAM heatmaps for sample predictions.  
**Deliverable:** `Phase-8/Day 127 - GradCAM.ipynb`.

---

# PHASE 9 — NLP FOUNDATIONS

**06 Oct 2026 to 18 Oct 2026**

### 06 Oct — Day 128 — NLP Basics
**Concept:** Tokenization, stopwords, stemming, lemmatization, cleaning.  
**Practice:** Build preprocessing pipeline for raw text.  
**Deliverable:** `Phase-9/Day 128 - NLP Basics.ipynb`.

### 07 Oct — Day 129 — Bag of Words Models
**Concept:** CountVectorizer and sparse matrix intuition.  
**Practice:** Convert text corpus into bag-of-words features.  
**Deliverable:** `Phase-9/Day 129 - BoW.ipynb`.

### 08 Oct — Day 130 — TF-IDF Weighted Vectors
**Concept:** TF, IDF, importance weighting.  
**Practice:** Build TF-IDF vectors and inspect top terms.  
**Deliverable:** `Phase-9/Day 130 - TFIDF.ipynb`.

### 09 Oct — Day 131 — Text Classification
**Concept:** Classical NLP pipeline with vectorizer + classifier.  
**Practice:** Train spam/sentiment classifier using LR and NB.  
**Deliverable:** `Phase-9/Day 131 - Text Classification.ipynb`.

### 10 Oct — Day 132 — Word Embeddings
**Concept:** Dense vectors and semantic similarity.  
**Practice:** Compare word similarity using pretrained embeddings or spaCy vectors.  
**Deliverable:** `Phase-9/Day 132 - Embeddings.ipynb`.

### 11 Oct — Day 133 — Regex for Text Parsing
**Concept:** Pattern extraction for text cleaning and structured parsing.  
**Practice:** Write patterns for emails, phone numbers, dates, URLs.  
**Deliverable:** `Phase-9/Day 133 - Regex.ipynb`.

### 12 Oct — Day 134 — Text Distance Metrics
**Concept:** Cosine similarity, Jaccard, edit distance intuition.  
**Practice:** Compare multiple short documents using different similarity metrics.  
**Deliverable:** `Phase-9/Day 134 - Similarity.ipynb`.

### 13 Oct — Day 135 — Sentiment Analysis Part 1
**Concept:** Text cleaning and train-ready preparation.  
**Practice:** Prepare movie review or product review dataset.  
**Deliverable:** `Phase-9/Day 135 - Sentiment Part 1.ipynb`.

### 14 Oct — Day 136 — Sentiment Analysis Part 2
**Concept:** Model training and evaluation.  
**Practice:** Train LR/NB sentiment classifiers and report metrics.  
**Deliverable:** `Phase-9/Day 136 - Sentiment Part 2.ipynb`.

### 15 Oct — Day 137 — Spam Classifier Project Part 1
**Concept:** End-to-end text project setup.  
**Practice:** Clean dataset and build TF-IDF pipeline.  
**Deliverable:** `Phase-9/Day 137 - Spam Part 1.ipynb`.

### 16 Oct — Day 138 — Spam Classifier Project Part 2
**Concept:** Final text project packaging.  
**Practice:** Save pipeline, create summary, and write README draft.  
**Deliverable:** `Phase-9/Day 138 - Spam Part 2.ipynb`.

### 17 Oct — Day 139 — Topic Modeling Overview
**Concept:** LDA intuition and unsupervised topic discovery.  
**Practice:** Run lightweight topic modeling on short corpus.  
**Deliverable:** `Phase-9/Day 139 - Topic Modeling.ipynb`.

### 18 Oct — Day 140 — Phase 9 Review & Sync
**Concept:** NLP review and artifact cleanup.  
**Practice:** Organize best NLP project and improve notebook narrative.  
**Deliverable:** `Phase-9/Day 140 - Sync.md`.

---

# PHASE 10 — TRANSFORMERS, EMBEDDINGS, RAG, AGENTS

**19 Oct 2026 to 30 Oct 2026**

### 19 Oct — Day 141 — Attention Mechanism Math
**Concept:** Query, key, value and weighted attention scores.  
**Practice:** Compute a toy attention matrix in NumPy.  
**Deliverable:** `Phase-10/Day 141 - Attention Math.ipynb`.

### 20 Oct — Day 142 — Transformer Architecture
**Concept:** Encoder blocks, self-attention, feedforward layers, positional encoding.  
**Practice:** Draw or explain a transformer data flow.  
**Deliverable:** `Phase-10/Day 142 - Transformer Architecture.ipynb`.

### 21 Oct — Day 143 — Hugging Face Pipelines
**Concept:** Quick inference with pretrained models.  
**Practice:** Run sentiment, summarization, and text generation pipelines.  
**Deliverable:** `Phase-10/Day 143 - HF Pipelines.ipynb`.

### 22 Oct — Day 144 — Tokenization & Model Inputs
**Concept:** Tokens, IDs, attention masks, truncation, padding.  
**Practice:** Tokenize raw text and inspect model-ready tensors.  
**Deliverable:** `Phase-10/Day 144 - Tokenization.ipynb`.

### 23 Oct — Day 145 — Fine-Tuning Workflow Overview
**Concept:** Datasets, tokenizer, trainer, metrics, epochs.  
**Practice:** Walk through a small fine-tuning example or dry-run structure.  
**Deliverable:** `Phase-10/Day 145 - Fine Tuning Workflow.ipynb`.

### 24 Oct — Day 146 — Embeddings & Semantic Search
**Concept:** Sentence embeddings and nearest-neighbor style retrieval.  
**Practice:** Encode sentences and rank similarity scores.  
**Deliverable:** `Phase-10/Day 146 - Semantic Search.ipynb`.

### 25 Oct — Day 147 — Vector Search with SentenceTransformers
**Concept:** Dense retrieval for practical semantic lookup.  
**Practice:** Build mini semantic retrieval over a small document set.  
**Deliverable:** `Phase-10/Day 147 - Vector Search.ipynb`.

### 26 Oct — Day 148 — RAG Pipelines & Chunking
**Concept:** Document chunking, retrieval before generation, context windows.  
**Practice:** Split text documents into chunks and prepare retrievable units.  
**Deliverable:** `Phase-10/Day 148 - RAG Chunking.ipynb`.

### 27 Oct — Day 149 — ChromaDB Integration
**Concept:** Vector DB basics and semantic retrieval.  
**Practice:** Store chunks in ChromaDB and retrieve top-k relevant results.  
**Deliverable:** `Phase-10/Day 149 - ChromaDB.ipynb`.

### 28 Oct — Day 150 — RAG Evaluation Basics
**Concept:** Retrieval quality, grounding, answer relevance.  
**Practice:** Manually inspect and score basic RAG outputs.  
**Deliverable:** `Phase-10/Day 150 - RAG Eval.ipynb`.

### 29 Oct — Day 151 — Agentic AI Basics
**Concept:** Tools, function calling, multi-step reasoning workflows.  
**Practice:** Build a toy tool-using flow or pseudo-agent logic.  
**Deliverable:** `Phase-10/Day 151 - Agent Basics.ipynb`.

### 30 Oct — Day 152 — Mini RAG/Agent Project
**Concept:** Combining retrieval and response generation into one demo.  
**Practice:** Build a simple RAG assistant over your own notes/docs.  
**Deliverable:** `Phase-10/Day 152 - Mini RAG Project.ipynb` or app script.

---

# PHASE 11 — REACT & WEB FUNDAMENTALS FOR ML

**31 Oct 2026 to 08 Nov 2026**

### 31 Oct — Day 153 — JavaScript Essentials
**Concept:** Variables, arrays, objects, functions, arrow functions, map/filter.  
**Practice:** Solve 10 small JS exercises.  
**Deliverable:** `Phase-11/Day 153 - JS Essentials.js`.

### 01 Nov — Day 154 — Forms & DOM Basics
**Concept:** DOM selection, event listeners, form submission handling.  
**Practice:** Build a simple page that reads inputs and displays result without reload.  
**Deliverable:** `Phase-11/Day 154 - DOM/index.html`.

### 02 Nov — Day 155 — Async JS & Fetch API
**Concept:** Promises, async/await, API requests.  
**Practice:** Fetch from a test API and render response.  
**Deliverable:** `Phase-11/Day 155 - Fetch/index.html`.

### 03 Nov — Day 156 — React Fundamentals
**Concept:** Components, JSX, props, basic structure.  
**Practice:** Create a starter React app with simple reusable components.  
**Deliverable:** `Phase-11/Day 156 - React Intro/src/`.

### 04 Nov — Day 157 — React Hooks
**Concept:** `useState`, `useEffect`, state-driven rendering.  
**Practice:** Build an input-driven component with dynamic updates.  
**Deliverable:** `Phase-11/Day 157 - Hooks/src/`.

### 05 Nov — Day 158 — React Forms for ML Inputs
**Concept:** Controlled forms and validation basics.  
**Practice:** Build a prediction form with numeric and categorical inputs.  
**Deliverable:** `Phase-11/Day 158 - React Forms/src/`.

### 06 Nov — Day 159 — Tailwind CSS Integration
**Concept:** Utility-first styling, grid, spacing, cards, buttons.  
**Practice:** Style prediction form and output cards using Tailwind.  
**Deliverable:** `Phase-11/Day 159 - Tailwind/src/`.

### 07 Nov — Day 160 — React + FastAPI Connection
**Concept:** Frontend-backend integration.  
**Practice:** Submit React form data to FastAPI endpoint and render prediction response.  
**Deliverable:** `Phase-11/Day 160 - React FastAPI/src/`.

### 08 Nov — Day 161 — Loading, Error, and Prediction UX
**Concept:** Inference user experience.  
**Practice:** Add spinner, error alert, empty state, and prediction card UI.  
**Deliverable:** `Phase-11/Day 161 - UX Polish/src/`.

---

# PHASE 12 — FULL-STACK AI INTEGRATION

**09 Nov 2026 to 15 Nov 2026**

### 09 Nov — Day 162 — Full Stack AI Architecture
**Concept:** End-to-end flow from browser to model prediction.  
**Practice:** Draw component interaction and deployment-level structure.  
**Deliverable:** `Phase-12/Day 162 - Architecture.md`.

### 10 Nov — Day 163 — Modular FastAPI Backend
**Concept:** APIRouter, settings, separation of concerns.  
**Practice:** Refactor backend into routes, schemas, services, utils.  
**Deliverable:** `Phase-12/backend/`.

### 11 Nov — Day 164 — Prediction API Hardening
**Concept:** Better validation, response models, edge case handling.  
**Practice:** Harden API for invalid categories, missing fields, type mismatch.  
**Deliverable:** updated `Phase-12/backend/`.

### 12 Nov — Day 165 — Full React Client
**Concept:** Structured frontend layout for ML product demo.  
**Practice:** Build dashboard-like client around prediction experience.  
**Deliverable:** `Phase-12/client/src/`.

### 13 Nov — Day 166 — Integration Testing
**Concept:** Verifying frontend-backend behavior across states.  
**Practice:** Test success, failure, empty input, server down scenarios.  
**Deliverable:** `Phase-12/Day 166 - Integration Notes.md`.

### 14 Nov — Day 167 — Auth Basics for Protected Endpoints
**Concept:** Token-based access control at a simple level.  
**Practice:** Add lightweight protected route concept to prediction API.  
**Deliverable:** `Phase-12/Day 167 - Auth Notes.md` + sample code.

### 15 Nov — Day 168 — End-to-End App Polish
**Concept:** Demo readiness and usability.  
**Practice:** Add final UI cleanup, screenshots, sample requests, and setup notes.  
**Deliverable:** polished mini full-stack AI app.

---

# PHASE 13 — PRODUCTION ML PIPELINES & MLOPS

**16 Nov 2026 to 30 Nov 2026**

### 16 Nov — Day 169 — Advanced sklearn Pipelines
**Concept:** ColumnTransformer, custom transformers, pipeline composition.  
**Practice:** Build a reusable end-to-end preprocessing + model pipeline.  
**Deliverable:** `Phase-13/Day 169 - sklearn Pipelines.ipynb`.

### 17 Nov — Day 170 — Config-Driven Training Setup
**Concept:** Central config values for paths, parameters, and reproducibility.  
**Practice:** Move model settings and paths into config file/module.  
**Deliverable:** `Phase-13/config.py` or YAML-based config.

### 18 Nov — Day 171 — MLflow Experiment Tracking
**Concept:** Logging params, metrics, artifacts, runs.  
**Practice:** Track a training run with model metrics and artifacts.  
**Deliverable:** `Phase-13/Day 171 - MLflow Tracking.ipynb`.

### 19 Nov — Day 172 — MLflow Model Registry
**Concept:** Registering and versioning trained models.  
**Practice:** Register best run output and document stage transition idea.  
**Deliverable:** `Phase-13/Day 172 - MLflow Registry.ipynb`.

### 20 Nov — Day 173 — Docker Production Patterns
**Concept:** Better Docker layering, requirements, runtime image cleanup.  
**Practice:** Improve previous Dockerfile for production friendliness.  
**Deliverable:** `Phase-13/Dockerfile`.

### 21 Nov — Day 174 — CI for Tests and Linting
**Concept:** Automated validation on push-like workflow.  
**Practice:** Write workflow file to run tests and optional lint checks.  
**Deliverable:** `Phase-13/ci.yml`.

### 22 Nov — Day 175 — CD Workflow Overview
**Concept:** Deployment automation concepts.  
**Practice:** Write a simplified deployment workflow outline or starter config.  
**Deliverable:** `Phase-13/cd.yml`.

### 23 Nov — Day 176 — SHAP Explainability
**Concept:** Post-hoc interpretability for tabular models.  
**Practice:** Generate summary and local explanations for one strong model.  
**Deliverable:** `Phase-13/Day 176 - SHAP.ipynb`.

### 24 Nov — Day 177 — Cloud Deployment Basics
**Concept:** App deployment targets, environment variables, serving architecture.  
**Practice:** Decide where to deploy API/frontend and document plan.  
**Deliverable:** `Phase-13/Day 177 - Deployment Plan.md`.

### 25 Nov — Day 178 — AWS S3 and EC2 Basics
**Concept:** Artifact storage and server basics.  
**Practice:** Write notes or demo script for uploading model artifacts to S3 and understanding EC2 role.  
**Deliverable:** `Phase-13/Day 178 - AWS Notes.ipynb`.

### 26 Nov — Day 179 — End-to-End ML Service Packaging
**Concept:** Packaging everything needed to serve inference.  
**Practice:** Bundle model, preprocessing, API, and environment requirements.  
**Deliverable:** deployable service folder.

### 27 Nov — Day 180 — Monitoring and Logging Basics
**Concept:** Tracking request flow, model errors, and health logs.  
**Practice:** Add request logging and basic monitoring notes to API.  
**Deliverable:** `Phase-13/Day 180 - Monitoring.md`.

### 28 Nov — Day 181 — Portfolio Project Infra Cleanup
**Concept:** Making projects look professional and consistent.  
**Practice:** Standardize project folder names, readmes, screenshots, and artifacts.  
**Deliverable:** polished project structure.

### 29 Nov — Day 182 — Capstone Planning
**Concept:** Final project selection and scope control.  
**Practice:** Choose domain, define problem, target users, metrics, and features.  
**Deliverable:** `Phase-13/Day 182 - Capstone Planning.md`.

### 30 Nov — Day 183 — Capstone Proposal
**Concept:** Turning idea into an execution-ready plan.  
**Practice:** Write concise proposal with stack, timeline, architecture, and success metrics.  
**Deliverable:** `Phase-13/Day 183 - Capstone Proposal.md`.

---

# PHASE 14 — CAPSTONE DEVELOPMENT

**01 Dec 2026 to 14 Dec 2026**

### 01 Dec — Day 184 — Capstone EDA
**Concept:** Understanding project dataset deeply before modeling.  
**Practice:** Run quality audit, target analysis, correlations, and baseline observations.  
**Deliverable:** `Phase-14/Day 184 - EDA.ipynb`.

### 02 Dec — Day 185 — Preprocessing Pipeline
**Concept:** Reusable preprocessing for production inference.  
**Practice:** Build and test the full preprocessing pipeline.  
**Deliverable:** `Phase-14/Day 185 - Preprocessing.ipynb`.

### 03 Dec — Day 186 — Baseline Modeling
**Concept:** Establishing reference performance.  
**Practice:** Train simple baseline models and document metrics.  
**Deliverable:** `Phase-14/Day 186 - Baseline.ipynb`.

### 04 Dec — Day 187 — Advanced Modeling
**Concept:** Better models and structured comparison.  
**Practice:** Train RF/XGBoost/SVM or relevant strong candidates.  
**Deliverable:** `Phase-14/Day 187 - Advanced Modeling.ipynb`.

### 05 Dec — Day 188 — Hyperparameter Tuning
**Concept:** Controlled optimization.  
**Practice:** Tune top model with randomized search or Optuna.  
**Deliverable:** `Phase-14/Day 188 - Tuning.ipynb`.

### 06 Dec — Day 189 — Model Explainability Audit
**Concept:** Trust, transparency, and interpretation.  
**Practice:** Use SHAP or equivalent explanation on final model.  
**Deliverable:** `Phase-14/Day 189 - Explainability.ipynb`.

### 07 Dec — Day 190 — Backend Development
**Concept:** Turning capstone model into usable API.  
**Practice:** Build FastAPI backend with schemas, model loading, and prediction route.  
**Deliverable:** `Phase-14/backend/`.

### 08 Dec — Day 191 — Frontend Development
**Concept:** Simple but polished user interface for inference.  
**Practice:** Build React/Tailwind frontend for capstone inputs and outputs.  
**Deliverable:** `Phase-14/frontend/src/`.

### 09 Dec — Day 192 — API Connection
**Concept:** Frontend-backend integration.  
**Practice:** Connect React form to FastAPI endpoint and render output cleanly.  
**Deliverable:** integrated app flow.

### 10 Dec — Day 193 — Client-Server QA
**Concept:** Robustness and edge-case handling.  
**Practice:** Test loading, errors, empty fields, invalid values, and response formatting.  
**Deliverable:** `Phase-14/Day 193 - QA Notes.md`.

### 11 Dec — Day 194 — Dockerization
**Concept:** Packaging application for deployment.  
**Practice:** Dockerize backend and, if possible, frontend.  
**Deliverable:** `Phase-14/Dockerfile`.

### 12 Dec — Day 195 — Deployment Setup
**Concept:** Final hosting preparation.  
**Practice:** Configure environment variables, startup commands, and deployment target docs.  
**Deliverable:** `Phase-14/Day 195 - Deployment.md`.

### 13 Dec — Day 196 — README, Screenshots, Architecture Docs
**Concept:** Presentation quality for recruiters and reviewers.  
**Practice:** Write full README with architecture diagram, setup instructions, screenshots, API contract.  
**Deliverable:** `Phase-14/README.md`.

### 14 Dec — Day 197 — Capstone Finalization
**Concept:** Final polish and demo readiness.  
**Practice:** Remove clutter, verify setup from scratch, prepare demo script.  
**Deliverable:** final capstone repository.

---

# PHASE 15 — JOB READINESS & PORTFOLIO LAUNCH

**15 Dec 2026 to 31 Dec 2026**

### 15 Dec — Day 198 — Resume Optimization
**Concept:** Results-focused AI/ML resume writing.  
**Practice:** Rewrite bullets around projects, metrics, deployment, and engineering stack.  
**Deliverable:** `Phase-15/Day 198 - Resume.md`.

### 16 Dec — Day 199 — GitHub Portfolio Refactoring
**Concept:** Strong project presentation.  
**Practice:** Select top projects, refine readmes, add screenshots and project summaries.  
**Deliverable:** `Phase-15/Day 199 - Portfolio.md`.

### 17 Dec — Day 200 — LinkedIn Profile Polish
**Concept:** Professional branding and discoverability.  
**Practice:** Update headline, about section, project descriptions, and featured links.  
**Deliverable:** `Phase-15/Day 200 - LinkedIn.md`.

### 18 Dec — Day 201 — Project Storytelling Practice
**Concept:** Explaining your work clearly to recruiters and interviewers.  
**Practice:** Write 2-minute and 5-minute explanations for your capstone and one ML project.  
**Deliverable:** `Phase-15/Day 201 - Storytelling.md`.

### 19 Dec — Day 202 — Interview Preparation Notes
**Concept:** ML fundamentals, deployment basics, project defense questions.  
**Practice:** Create structured answers for likely interview questions.  
**Deliverable:** `Phase-15/Day 202 - Interview Notes.md`.

### 20 Dec — Day 203 — Apply to Roles Batch 1
**Concept:** Application pipeline setup.  
**Practice:** Apply to first batch of ML/AI roles and track role links, dates, status.  
**Deliverable:** `Phase-15/Day 203 - Applications.md`.

### 21 Dec — Day 204 — Weak Topic Review
**Concept:** Focused revision of weak areas.  
**Practice:** Revisit 2 weak domains such as calibration, SHAP, APIs, PyTorch training.  
**Deliverable:** `Phase-15/Day 204 - Weak Topics.md`.

### 22 Dec — Day 205 — Apply to Roles Batch 2
**Concept:** Consistent application momentum.  
**Practice:** Apply to additional set of targeted roles.  
**Deliverable:** updated application tracker.

### 23 Dec — Day 206 — Mock Demo Recording
**Concept:** Demo confidence and communication.  
**Practice:** Record yourself presenting capstone in 5 minutes.  
**Deliverable:** `Phase-15/Day 206 - Demo Notes.md`.

### 24 Dec — Day 207 — Portfolio README Improvements
**Concept:** Better recruiter readability.  
**Practice:** Improve intros, results sections, and setup clarity on top repos.  
**Deliverable:** refined READMEs.

### 25 Dec — Day 208 — Capstone Walkthrough Notes
**Concept:** Interview-friendly project narration.  
**Practice:** Write structured walkthrough: problem → data → model → deployment → tradeoffs.  
**Deliverable:** `Phase-15/Day 208 - Capstone Walkthrough.md`.

### 26 Dec — Day 209 — Mock Interview Round 1
**Concept:** First timed simulation.  
**Practice:** Answer ML + project + API questions aloud.  
**Deliverable:** `Phase-15/Day 209 - Mock 1.md`.

### 27 Dec — Day 210 — Mock Interview Round 2
**Concept:** Improved second simulation.  
**Practice:** Repeat with sharper and shorter answers.  
**Deliverable:** `Phase-15/Day 210 - Mock 2.md`.

### 28 Dec — Day 211 — Final Repo Cleanup
**Concept:** Last-mile polish.  
**Practice:** Remove unused files, standardize folder names, verify instructions.  
**Deliverable:** cleaned final repositories.

### 29 Dec — Day 212 — Final Application Push
**Concept:** Closing the loop on portfolio + applications.  
**Practice:** Apply to another targeted set and send follow-ups where possible.  
**Deliverable:** final tracker update.

### 30 Dec — Day 213 — 2027 Skill Gap Planning
**Concept:** Next-level growth planning after roadmap completion.  
**Practice:** Identify what to deepen next: cloud, LLMOps, advanced DL, distributed training, etc.  
**Deliverable:** `Phase-15/Day 213 - 2027 Plan.md`.

### 31 Dec — Day 214 — Celebrate & Reflect
**Concept:** Reflection and confidence building.  
**Practice:** Review projects completed, strengths built, weak spots remaining, and hiring readiness.  
**Deliverable:** `Phase-15/Day 214 - Reflection.md`.

---

# Final Outcome Targets

By the end of this roadmap, aim to have:
- **3 strong classical ML projects**
- **1 deep learning project**
- **1 CV or NLP project**
- **1 RAG/LLM-based project**
- **1 deployed end-to-end capstone**
- **multiple production-style repos** with clean structure, tests, docs, and artifacts
- **resume, LinkedIn, portfolio, and interview notes ready**
- **consistent job application tracking completed**

---

# Final Reminder

This version intentionally prioritizes:
- practical AI/ML engineering output
- deployable and demonstrable work
- portfolio strength
- strong classical ML + modern LLM exposure
- reasonable breadth without low-ROI overload
