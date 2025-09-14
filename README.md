# <b>Customer Churn Prediction<b>
<hr>
<b>📌 Project Overview<b>
This project focuses on predicting customer churn for a telecom company.
Churn — the phenomenon of customers discontinuing a service — is a critical business problem in industries where long-term customer retention drives profitability.
Using customer behavior and service data, this project applies machine learning techniques to identify customers at risk of leaving, with the goal of supporting proactive retention strategies.
<hr>
<b>🎯 Objectives<b>
•	Analyze customer data to uncover patterns linked to churn.<br>
•	Apply and compare machine learning models for churn prediction.<br>
•	Provide actionable business recommendations to reduce churn.
<hr>
<b>⚙️ Methodology<b>
The notebook follows a complete data science workflow:
1.	Business Understanding – framing churn as a profitability issue.<br>
2.	Data Exploration & Cleaning – handling missing values and imbalances.<br>
3.	Preprocessing & Feature Engineering – encoding categorical variables, scaling, and resampling.<br>
4.	Modeling – Logistic Regression and Random Forest.<br>
5.	Hyperparameter Tuning – RandomizedSearchCV with Stratified K-Fold cross-validation.<br>
6.	Evaluation – accuracy, precision, recall, F1-score, ROC-AUC.<br>
7.	Interpretation – coefficients (Logistic Regression) and feature importance (Random Forest).
<hr>



<b>📊 Results<b>
•	Logistic Regression: provided an interpretable baseline with decent recall.<br>
•	Random Forest: achieved stronger predictive power and balanced performance across metrics.<br>
•	Key Features Influencing Churn: contract type, tenure, monthly charges, and service-related attributes.
<hr>
<b>🏢 Business Recommendations<b>
•	Implement loyalty and retention programs targeting high-risk customers.<br>
•	Enhance customer service quality and responsiveness.<br>
•	Use predictive segmentation to guide marketing campaigns.<br>
•	Improve product bundles and flexible contracts to reduce churn incentives.<br>
•	Collect customer feedback regularly to adapt strategies.
<hr>
<b>📂 Repository Structure<b>
 - <b>churnintel.ipynb<b>      # Main Jupyter notebook<br>
 <b>README.md<b>              # Project documentation<br>
 <b>data/<b>                  # dataset storage<br>
 <b>models/<b>                # (Soon) saved trained models<br>
 
<hr>
<b>📌 Tech Stack<b>
•	Python<br>
•	scikit-learn – modeling and evaluation<br>
•	imbalanced-learn – SMOTE for class imbalance<br>
•	pandas, numpy – data manipulation<br>
•	matplotlib, seaborn – visualization
<hr>
<b>📈 Future Work<b>
•	Explore deep learning models (e.g., neural networks).<br>
•	Integrate real-time churn prediction into a business dashboard.<br>
•	Expand analysis with additional customer experience data.
