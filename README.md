# Netflix-Data-science-project
Netflix Data Insights & Predictive Modeling 🎬
Project Overview 🚀
This project presents an end-to-end data science pipeline to analyze and predict content trends on the Netflix platform. From data cleaning and feature engineering to building a predictive classification model, this repository demonstrates the ability to translate raw dataset artifacts into actionable intelligence.
Technical Highlights 🛠️
 Data Wrangling: Handled complex missing values, performed temporal feature engineering (extracting years/months), and standardized multi-categorical features (e.g., country normalization).
 Pipeline Architecture: Utilized Scikit-learn ⁠Pipeline⁠ and ⁠ColumnTransformer⁠ to create a robust, production-ready workflow for categorical encoding and model training.
 Predictive Modeling: Implemented a ⁠RandomForestClassifier⁠ (optimized with 200 estimators) to classify content types (Movie vs. TV Show) based on metadata.
 Insight Generation: Conducted comprehensive Exploratory Data Analysis (EDA) using ⁠Seaborn⁠ and ⁠Matplotlib⁠ to identify growth patterns and genre distributions.
Model Performance 📊
The model achieved high accuracy in predicting content types, with feature importance analysis highlighting the critical role of release years and content ratings in defining the structure of Netflix's library.
Project Workflow 🧠
1 Preprocessing: Data cleaning (imputation), type conversion, and handling duplicate records.
2 Exploratory Data Analysis (EDA): Visualizing top content-producing countries, rating distributions, and genre popularity.
3 Machine Learning: Automated pipeline deployment, model training, and evaluation via ⁠classification_report⁠ and ⁠Confusion Matrix⁠ analysis.
4 Feature Importance: Quantifying the impact of specific metadata attributes on the classification task.
Technologies Used 💻
 Python (Pandas, NumPy)
 Scikit-Learn (Preprocessing, Pipelines, Ensemble Methods)
 Visualization: Seaborn, Matplotlib
Key Business Takeaways 📈
 Strategic Growth: Demonstrated that a significant surge in content library expansion occurred post-2015.
 Market Concentration: Identified the United States as the primary contributor to the platform's content ecosystem.
 Content Strategy: The popularity of specific ratings (e.g., TV-MA) serves as a key indicator for target audience demographics.
