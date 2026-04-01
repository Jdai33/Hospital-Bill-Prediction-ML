🏥 Project Overview
This project aims to develop a predictive system that estimates individual medical costs and hospital charges based on historical claim data. By leveraging machine learning, hospitals and insurance providers can automate budget planning, resource allocation, and risk assessment.

📊 Dataset Description
The model is trained on medical claim data, typically containing the following features:
Demographics: Age, sex, and residential region.
Health Indicators: Body Mass Index (BMI), smoker status, and presence of chronic ailments.
Family Details: Number of children or dependents.
Target Variable: Charges — the individual medical costs billed by the hospital.

⚙️ Methodology
The project follows a standard ML lifecycle:
1. Exploratory Data Analysis (EDA): Visualizing feature distributions (e.g., age vs. charges) and identifying correlations.
2. Data Preprocessing: Handling missing values, normalizing numerical data, and converting categorical variables using techniques like one-hot encoding.
3. Model Training: Training multiple algorithms to find the best performer. Common models include:
    Linear Regression
    Random Forest Regression
    Gradient Boosting (XGBoost/LightGBM)
4. Evaluation: Metrics like Mean Absolute Error (MAE) and R² score are used to validate accuracy.

