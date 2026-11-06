King County House Price Prediction Using CNN

📌Project Overview

This project focuses on predicting residential house prices using a Convolutional Neural Network (CNN) and the House Sales dataset.

The model uses 18 property-related features, including the number of bedrooms and bathrooms, living area, lot size, property condition, grade, location, and year built, to estimate house prices.

The main objective is to explore how deep learning techniques can be applied to structured housing data and evaluate their effectiveness in predicting property values.

🎯 Project Objectives

- Explore and understand the King County housing dataset.
- Perform data cleaning and exploratory data analysis (EDA).
- Analyse relationships between housing features and property prices.
- Prepare and scale input features for model training.
- Develop a CNN-based regression model.
- Compare CNN performance with traditional machine learning algorithms.
- Evaluate model performance using regression metrics.

📊 Dataset

The project uses the King County House Sales dataset, which contains residential property sales information.

The dataset includes the following 18 input features:

| Feature | Description |
|---|---|
| bedrooms | Number of bedrooms |
| bathrooms | Number of bathrooms |
| sqft_living | Interior living area in square feet |
| sqft_lot | Total lot area in square feet |
| floors | Number of floors |
| waterfront | Whether the property has a waterfront view |
| view | Property view rating |
| condition | Overall property condition |
| grade | Overall construction and design grade |
| sqft_above | Above-ground living area |
| sqft_basement | Basement area |
| yr_built | Year the property was built |
| yr_renovated | Year of renovation |
| zipcode | Property ZIP code |
| lat | Latitude |
| long | Longitude |
| sqft_living15 | Average living area of nearby properties |
| sqft_lot15 | Average lot area of nearby properties |

Target variable: `price` – The selling price of the property.

🛠️ Technologies and Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

🔍 Project Workflow

1. Data Understanding and Preprocessing
- Loaded and examined the housing dataset.
- Checked data types, missing values, and duplicate records.
- Prepared the dataset for analysis and model development.

2. Exploratory Data Analysis (EDA)
- Analysed the distribution of house prices.
- Investigated relationships between property features and prices.
- Used correlation analysis and visualisations to identify important patterns.
- Examined geographical and property-related factors affecting house prices.

3. Feature Scaling
Applied Min-Max Scaling to transform numerical features into a consistent range, helping prepare the data for CNN training.

4. Model Development
Developed a Convolutional Neural Network (CNN) regression model using TensorFlow and Keras to learn patterns from the housing features and predict property prices.

5. Model Evaluation and Comparison
Evaluated the CNN model and compared its performance with traditional machine learning approaches:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Support Vector Regression (SVR)
- CNN with Min-Max Scaling
- CNN with Standard Scaling

Performance was assessed using regression evaluation metrics, including:

- R² Score
- Mean Squared Error (MSE)

📈 Model Results

The CNN model using Min-Max Scaling achieved an R² score of approximately **0.8813 (88.13%)** in the initial evaluation.

This indicates that the model explained approximately 88.13% of the variance in the target house prices on the evaluated dataset.

| Model | R² Score |
|---|---:|
| Linear Regression | 0.5717 |
| Decision Tree | 0.7679 |
| Random Forest | 0.8716 |
| SVR | 0.8409 |
| CNN with Min-Max Scaling | 0.8813 |
| CNN with Standard Scaling | 0.8744 |

Note: Results are based on the initial model evaluation and may vary depending on data preprocessing, train-test splitting, and model configuration.*

🚀 How to Run the Project

Prerequisites

Make sure Python and Jupyter Notebook are installed.

1. Clone the Repository
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git

2. Navigate to the Project Directory

cd YOUR-REPOSITORY-NAME

3. Install Dependencies

pip install pandas numpy matplotlib seaborn scikit-learn tensorflow jupyter

4. Launch Jupyter Notebook
5. Run the Notebook

Open the project notebook and execute the cells in sequence to perform data exploration, preprocessing, model training, and evaluation.

💡 Key Learning Outcomes

- Practical experience with regression problems.
- Understanding and applying exploratory data analysis.
- Working with feature scaling techniques.
- Building deep learning models using TensorFlow and Keras.
- Comparing traditional machine learning algorithms with CNN-based regression.
- Evaluating predictive performance using regression metrics.

🔮 Future Improvements

- Experiment with additional deep learning architectures.
- Perform hyperparameter tuning to improve prediction accuracy.
- Apply cross-validation for more reliable model evaluation.
- Investigate feature selection and engineering techniques.
- Explore more advanced approaches for handling geographical and categorical features.

👤 Author

Udaya Singh Rai

GitHub: [Your GitHub Profile](https://github.com/udrai10)



PS: If you find this project interesting, feel free to explore the repository and share your feedback!