# Mobile-Price-Classification-Using-Machine-Learning
📱 Mobile Price Classification Using Machine Learning

This project aims to predict the price range of mobile phones (Low, Medium, High, Very High) based on various features like RAM, battery power, screen resolution, etc., using multi-class classification techniques.

💾 Dataset
Source: Kaggle Mobile Price Classification Dataset

Records: 2000 samples with 21 features

Target Variable: price_range (0 to 3)

🧠 Key Concepts Learned
Explored how different ML models (Random Forest, SVM, KNN, Naive Bayes) handle multi-class classification

Gained deeper understanding of class-specific metrics like F1-scores, precision, recall, and confusion matrices

Learned how multi-class setups influence feature selection, scaling, and model architecture

📊 Techniques Used
Feature engineering (e.g. combining pixel height × width to form screen_resolution)

Scaling with StandardScaler

Model comparison using cross-validation

Feature importance analysis for dimensionality reduction

Hyperparameter tuning with RandomizedSearchCV

🚀 Best Model
Random Forest Classifier

Accuracy: ~86.6%

Most important features: ram, screen_resolution, battery_power, and int_memory
📬 Connect
Have ideas or questions about multi-class classification or ML pipelines? Let’s connect on LinkedIn and grow together!
