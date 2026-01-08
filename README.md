📊 Kraljic Matrix Category Predictor
🔹 Project Description

1.This project predicts the Kraljic Matrix category of a product

2.It uses Machine Learning (Random Forest model)

3.The project is built using Python and Streamlit

4.Users can enter product and supplier details to get predictions

🔹 What is Kraljic Matrix?

1.A supply chain classification model

2.Categories products based on:

3.Supply Risk

4.Profit Impact

5.Helps in better purchasing and sourcing decisions

🔹 Project Files

1.kraljik_category.py – Streamlit web application

2.kraljic_category.ipynb – Jupyter Notebook (model building & testing)

3.random_forest_model.joblib – Trained ML model

4.README.md – Project documentation

🔹 Technologies Used

1.Python 🐍

2.Streamlit

3.Pandas

4.Joblib

5.Machine Learning (Random Forest)

🔹 Input Features

1.Product Name

2.Supplier Region

3.Lead Time (Days)

4.Order Volume (Units)

5.Cost per Unit

6.Supply Risk Score (1–5)

7.Profit Impact Score (1–5)

8.Environmental Impact Score (1–5)

9.Single Source Risk (Yes / No)

🔹 Output

1.Predicts one Kraljic Category for the product

2.Result is displayed on the Streamlit app screen

🔹 How the Project Works

1.User enters product details in the form

2.Input data is sent to the trained ML model

3.Model predicts the Kraljic category

4.Result is shown instantly

🔹 How to Run the Project

1.Install required libraries:
pip install streamlit pandas joblib


2.Run the Streamlit app:
streamlit run kraljik_category.py


3.Open the browser link shown in terminal
Enter product details and click Predict

🔹 Use Case

1.Supply Chain Management

2.Procurement Strategy

3.Risk Analysis

4.Purchasing Decision Support

🔹 Conclusion

1.This project helps classify products using the Kraljic Matrix

2.It makes procurement decisions easier and data-driven

3.Useful for students and supply chain professionals
