# 🎯 The 100-Project Blueprint (Ordered: Basic to Advanced)

This document contains a structured, chronologically-ordered catalog of **100 Machine Learning and AI engineering projects** sorted from basic to advanced difficulty. They are designed to follow your learning progression, ensuring a project-focused, "build-in-public" engineering profile.

---

## 📈 Part 1: Basic Machine Learning Foundations (Projects 1 - 25)
*Focus: Data preprocessing, pipeline verification, metrics, basic classification, and outlier handling.*

1. **Pipeline Verification Utility** - Preprocessing unit tests verifying data types and shape stability.
2. **Sigmoid Function Visualizer** - Plot of odds ratios and log-odds mapped to sigmoid probabilities.
3. **Binary Classification on Iris** - Binary mapping classifier with custom decision thresholds.
4. **Log Loss Calculator from Scratch** - Custom log loss formula compared against `sklearn.metrics`.
5. **Titanic Survival Predictor** - Baseline logistic regression classifier using default thresholds.
6. **Multiclass Softmax Classifier** - Multi-category classifier trained on the Wine dataset.
7. **Metrics Calculator from Scratch** - Custom precision, recall, and F1 calculations.
8. **ROC & Precision-Recall Profiler** - Curves evaluating metric behavior on skewed target classes.
9. **Missingness Taxonomy Profiler** - Statistical test suite identifying MCAR/MAR/MNAR null patterns.
10. **Advanced Imputation Benchmarker** - KNNImputer vs IterativeImputer comparison on California housing.
11. **Outlier Detector Suite** - Isolation Forest & LOF comparison for anomaly cleaning.
12. **Custom Winsorization Transformer** - Custom sklearn-compatible transformer class to clip outliers.
13. **Cyclic Encodings for Temporal Data** - Sine/cosine transformation pipeline for dates & weekdays.
14. **KNN Distance Metrics Analyzer** - KNN classifier evaluating Euclidean vs Manhattan distance metrics.
15. **SMS Text Spam Classifier** - Naive Bayes model using TF-IDF for SMS spam/ham classification.
16. **Heart Disease Classifier Preprocessor** - Clean `ColumnTransformer` pipelines separating scaling and encoding.
17. **Heart Disease Model Optimizer** - Hyperparameter optimization using Grid and Randomized search.
18. **Classifier Calibration Profiler** - Reliability curves with Platt scaling and Isotonic regression calibration.
19. **Entropy & Gini Split Calculator** - Interactive manual split calculator mapping information gain.
20. **Decision Tree Complexity Visualizer** - Decision boundary visualization mapping depth vs pruning.
21. **Random Forest Classifier** - Breast cancer diagnosis classifier utilizing ensemble trees.
22. **OOB Error vs Validation Plotter** - Dynamic tracker mapping Out-of-Bag error trends during training.
23. **AdaBoost Classifier from Scratch** - Custom training loop updating sample weights and decision stumps.
24. **Gradient Boosting Classifier** - Custom loss gradient boosting classifier.
25. **Support Vector Machine (SVM) Kernel Plotter** - Visual plots comparing Linear, Polynomial, and RBF kernels.

---

## 🌲 Part 2: Intermediate Machine Learning & Core Algorithms (Projects 26 - 50)
*Focus: Advanced boosting, clustering, recommender systems, forecasting, and tabular datasets.*

26. **XGBoost vs LightGBM Benchmarker** - Execution speed and metric profiling on a large dataset.
27. **CatBoost Optuna Optimizer** - Automated hyperparameter tuning dashboard using Optuna.
28. **Heterogeneous Stacking Ensemble** - Stacking classifier using RF, LogReg, and SVM meta-learners.
29. **K-Means Silhouette Optimizer** - Elbow and Silhouette plots for optimal cluster evaluation.
30. **DBSCAN Customer Segmenter** - Density-based clustering profile identifying outlier segments.
31. **Dimensionality Reducer (PCA)** - Principal components variance analyzer and coordinate projection.
32. **Prophet vs ARIMA Sales Forecaster** - Forecast overlay mapping monthly metrics and seasonal trends.
33. **Content-Based Movie Recommender** - Recommendation engine matching titles via Cosine Similarity.
34. **Collaborative Filtering Recommender** - Matrix factorization or SVD-based rating prediction.
35. **Customer Churn Predictor** - Customer churn model using XGBoost on telecom data.
36. **Credit Risk Classifier** - Predict loan default probability using regularized logistic regression.
37. **House Price Regressor** - Advanced regression modeling with Ridge, Lasso, and ElasticNet.
38. **Bike Sharing Demand Forecaster** - Time series regression combining weather and calendar features.
39. **Employee Attrition Classifier** - Logistic regression and Random Forest to classify turnover risks.
40. **Anomaly Detection in Network Traffic** - One-Class SVM and Isolation Forest on network logs.
41. **E-commerce Customer Life Time Value (LTV) Predictor** - Regression predicting future purchase value.
42. **Automobile Fuel Efficiency Regressor** - Multivariate regression model with interaction features.
43. **Music Genre Classifier** - KNN and Random Forest classifier trained on audio feature vectors.
44. **Hotel Booking Cancellation Predictor** - Model classifying reservation cancellation probabilities.
45. **Sensor Failure Predictor** - Binary classifier predicting industrial sensor breakdowns.
46. **Student Performance Regressor** - Grade prediction based on demographic and study habit features.
47. **Air Quality Index (AQI) Predictor** - Regression modeling particulate matter concentrations.
48. **Online Fraud Transaction Detector** - Class-imbalanced classification using SMOTE and Random Forest.
49. **Store Sales Forecast Predictor** - Multi-store demand forecasting using ensemble regression trees.
50. **Telco Customer Segmentation** - Customer clustering using K-Means and PCA visualization.

---

## 🧠 Part 3: Deep Learning & Computer Vision (Projects 51 - 70)
*Focus: Perceptrons, PyTorch core models, ConvNets, transfer learning, and image-generative techniques.*

51. **Single Perceptron from Scratch** - Forward/backward pass mapping logical gates.
52. **Activation Functions Sandbox** - Plotting gradients and derivatives of Sigmoid, ReLU, and Tanh.
53. **BCE vs MSE Loss Gradient Simulator** - Visual optimization paths for binary classification.
54. **Keras Sequential MLP on MNIST** - Neural network reaching >95% handwritten digit recognition.
55. **Keras Functional Multi-Input Network** - Model joining continuous features and categorical features.
56. **PyTorch Autograd Playground** - Computational graph backpropagation calculator.
57. **PyTorch Custom Tabular DataLoader** - Custom generator for large batch processing.
58. **PyTorch MLP Training Loop** - Full neural network loop from zero_grad to optimizer steps.
59. **PyTorch Early Stopper Callback** - Halts training based on validation loss stabilization.
60. **PyTorch Regularization Benchmarker** - Comparison of L1/L2 weight decay and Dropout rates.
61. **PyTorch Custom CNN Classifier** - Convolutional model with max pooling on FashionMNIST.
62. **Image Augmentation Pipeline** - Vision augmentations (flip, crop, rotate) using torchvision.
63. **Transfer Learning Image Engine** - Fine-tuned ResNet50 on a custom image category dataset.
64. **Grad-CAM Attention Overlay** - Heatmap highlighting critical image regions for CNN classification.
65. **Image Compression Autoencoder** - Autoencoder model reducing image dimensions to latent code.
66. **VAE Digit Generator** - Variational Autoencoder creating new digit samples from latent vectors.
67. **Stable Diffusion Text-to-Image Runner** - Text-guided image synthesis using Diffusers.
68. **Stable Diffusion Image-to-Image Client** - Prompt-guided modification of source images.
69. **CNN Architecture Optimizer** - Optuna-driven automation search for layers and learning rates.
70. **Real-time Object Detection API** - FastAPI endpoint running YOLOv8 detection on uploaded images.

---

## 🔤 Part 4: NLP, Transformers, RAG & Agents (Projects 71 - 85)
*Focus: Text processing, spaCy parsing, BERT classification, Vector Stores, and agentic reasoning.*

71. **Regex Text Cleaning Utility** - Cleaning raw text inputs (stripping HTML, punctuation, and stopwords).
72. **Bag of Words vs TF-IDF Classifier** - Text representation evaluation on movie reviews.
73. **Word2Vec Semantic Explorer** - Load pre-trained word vectors and perform vector algebra.
74. **spaCy Pipeline Custom Component** - Extension module modifying spaCy document tokens.
75. **spaCy Named Entity Recognition (NER)** - Custom NER training to identify specific entities.
76. **Multi-Engine Sentiment Analyzer** - NLTK VADER vs TextBlob scoring of social media posts.
77. **Document Similarity Finder** - Cosine similarity matches for document deduplication.
78. **Attention Matrix Heatmap Visualizer** - Self-attention visualization mapping token dependencies.
79. **Hugging Face Zero-Shot Classifier** - Pipeline sorting text into user-defined categories.
80. **BERT Fine-Tuner for Sentiment Analysis** - Hugging Face BERT classifier trained via Trainer API.
81. **BERT Local Model Server** - Serialized BERT model inference wrapper.
82. **Document Vector Store (RAG 1)** - ChromaDB and LangChain document chunking and vector indexing.
83. **RAG QA Chat System (RAG 2)** - Context-aware document querying with Ollama/Llama.
84. **RAG Evaluation Suite** - Automated validation of answers using DeepEval/RAGAS.
85. **Custom ReAct Framework AI Agent** - Tool-calling agent routing queries to calculator and search tools.

---

## ⚙️ Part 5: Production Scaffolding, APIs & Web Integration (Projects 86 - 95)
*Focus: FastAPI services, validation schemas, Docker configs, Celery async systems, and React dashboards.*

86. **FastAPI Model Predictor API** - Serialized model loader serving endpoints.
87. **Pydantic Request Validator** - Validation schemas checking parameter boundaries.
88. **ML API Exception Handler** - Custom errors returning clean diagnostic JSON messages.
89. **FastAPI Route Tester** - Automated API tests running via Pytest.
90. **Multi-Model API Router** - Organized routing tree separating models by phase.
91. **Dockerized Inference Container** - Dockerfile packaging app dependencies and model parameters.
92. **Docker Compose Orchestrator** - Orchestrates connection between API container and Redis cache.
93. **Celery Async prediction queue** - Queue system processing batch predictions asynchronously.
94. **React Prediction Form Console** - Component capturing user parameters with boundary checks.
95. **React Analytics Dashboard** - Dashboard displaying past prediction trends via Chart.js.

---

## 🚀 Part 6: MLOps Pipelines & Capstone Projects (Projects 96 - 100)
*Focus: MLOps pipelines (DVC/Feast/MLflow/BentoML) and packaging flagship applications.*

96. **DVC Pipeline Version Tracker** - Stage-locked pipeline versioning data and weights.
97. **Feast Feature Store** - Unified store supplying features to online and offline jobs.
98. **MLflow Experiment Logger** - Centralized logging database tracking metrics and runs.
99. **BentoML Service Packager** - Packages model logic into a deployable serving system.
100. **Full-Stack Capstone System** - Integrates React UI, FastAPI backend, MongoDB history, and BentoML model server inside a multi-container Docker Compose.
