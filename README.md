🥗 Sustainable Indian Diet – Carbon Footprint Analysis using Machine Learning
📘 Project Overview

This project analyzes the environmental sustainability of Indian food items by studying their carbon footprint in relation to their nutritional values.
It uses data analysis, clustering, and machine learning regression to identify eco-friendly food choices and predict their carbon impact.

Dataset Source: Nutritional and Carbon Footprint Data of Indian Diet (Kaggle)

🗓️ Weekly Progress
🧩 Week 1 – Data Cleaning, EDA & Clustering

Objective:
To clean and analyze the dataset, understand the relationship between nutrition and carbon footprint, and cluster foods based on sustainability.

Work Done:

Imported and preprocessed data by handling missing values and standardizing column names.

Performed Exploratory Data Analysis (EDA) using Matplotlib and Seaborn:

Distribution of carbon footprint among food items

Relationship between energy and carbon footprint

Top 10 foods with the highest carbon emissions

Selected key features: Energy(kcal), Proteins, Carbohydrates, Fats, Fiber, and Carbon Footprint(kg CO2e).

Applied K-Means Clustering to group foods into sustainability categories.

Visualized clusters using PCA (Principal Component Analysis).

Exported the processed dataset (clustered_indian_diet_sustainability.csv).

Key Learnings:

Understood how nutritional factors influence sustainability.

Learned how to perform EDA and apply unsupervised learning in real-world data.

⚙️ Week 2 – Model Optimization & Cluster Evaluation

Objective:
To optimize clustering, evaluate its performance, and extract meaningful sustainability insights.

Work Done:

Used Elbow Method to identify the optimal number of clusters.

Calculated Silhouette Score to measure cluster quality.

Re-trained K-Means with optimal clusters and visualized them using PCA.

Generated cluster summaries highlighting:

High-carbon, high-fat foods (less sustainable)

Balanced foods with moderate impact

Low-carbon, nutrient-rich foods (most sustainable)

Saved enhanced results (Week2_Sustainability_Model_Enhanced.csv).

Key Learnings:

Learned cluster validation and interpretability techniques.

Gained insights into sustainable versus high-impact foods.

🧠 Week 3 – Carbon Footprint Prediction using Regression

Objective:
To build predictive models that estimate the carbon footprint of foods based on their nutritional components.

Work Done:

Defined independent features (nutrients) and target variable (carbon footprint).

Split data into training and testing sets.

Trained two regression models:

Linear Regression

Random Forest Regressor

Evaluated models using MAE, RMSE, and R² score.

Random Forest performed best with higher accuracy.

Analyzed feature importance to determine which nutrients most influence carbon emissions.

Saved prediction results (Week3_Carbon_Footprint_Predictions.csv).

Key Learnings:

Learned to build and compare regression models.

Understood how individual nutrients affect sustainability.

Random Forest proved more reliable for prediction tasks.
