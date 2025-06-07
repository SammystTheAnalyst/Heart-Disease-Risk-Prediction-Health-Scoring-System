🫀 Heart Disease Risk Prediction & Patient Health Scoring System

This project leverages machine learning to predict heart disease risk using patient data. It explores feature correlations, demographic trends, and risk factor analysis. The pipeline includes clustering patients into risk groups, building a health scoring system, and supporting real-time multi-disease prediction integration.


📌 Project Overview

Heart disease remains a leading cause of death worldwide. This project aims to use predictive analytics to identify individuals at risk, understand contributing factors, and provide data-driven insights that can assist in early intervention and decision-making.


🎯 Project Objectives

- Predict the likelihood of heart disease based on patient health metrics.
- Analyze risk factors and their interactions.
- Explore trends in heart disease based on demographic features.
- Cluster patients into risk categories using unsupervised learning.
- Develop a scoring system to interpret patient health beyond binary prediction.
- Integrate findings into a real-time, multi-disease prediction system.

🛠️ Methodologies & Tools Used

- Language: Python  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `plotly`, `joblib`
- Machine Learning: Logistic Regression, Decision Trees, Random Forests
- Clustering: K-Means for risk group segmentation
- Feature Engineering: Correlation matrix, one-hot encoding, normalization
- Model Evaluation: Accuracy, Precision, Recall, ROC-AUC
- Deployment: Streamlit (used in an extended application layer)

📊 Observations & Insights

🔗 Correlation & Feature Interactions
Exploratory analysis revealed strong correlations between age, cholesterol levels, and the presence of disease. Feature interaction plots showed how combinations, such as high BMI and low sleep, increase the risk.

⚠️ Risk Factor Analysis
Using model feature importances and statistical analysis, factors such as triglyceride levels, homocysteine, and family history were identified as key risk drivers.

👥 Demographic Trends
The risk of heart disease increased with age and was more prevalent among individuals reporting high stress levels, poor sleep, and elevated BMI.

🧪 Patient Clustering
Patients were segmented into 3 distinct risk groups using K-Means, providing personalized insights and targeted health interventions.

📈 Patient Health Scoring System
A weighted scoring system was developed to assess patient health on a 0–100 scale, offering a more nuanced measure beyond binary classification.

🌐 Multi-Disease Prediction Integration
This project was designed to be part of a larger real-time diagnostic system capable of handling multiple diseases using shared features and an expandable prediction architecture.


📁 Repository Contents

- `notebooks/`: Jupyter notebooks with full analysis and modeling workflow  
- `models/`: Serialized machine learning models (`.pkl` files)  
- `data/`: Cleaned datasets (without sensitive personal info)   
- `README.md`: Project documentation

🚀 Future Plans

- Add support for more diseases (e.g., diabetes, kidney disease)
- Enhance clustering with deep learning-based embeddings
- Deploy as a full web app with database support and API access

📬 Contact

For questions, suggestions, or collaborations:  
Email: sammysttheanalyst@gmail.com  
YouTube: [@sammysttheanalyst](https://www.youtube.com/@sammysttheanalyst)
