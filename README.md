# 🏦 Loan Approval Prediction

This Streamlit web application helps users predict their loan eligibility based on financial, personal, and employment-related inputs. Built with machine learning and data science tools, it offers a user-friendly way to simulate loan eligibility outcomes.

## 📌 Overview

Predicting loan eligibility is an essential task for financial institutions. This project leverages classification algorithms to automate and simplify that decision-making process. Users can input relevant details and receive a prediction based on a trained model.

## Project Structure

Loan-Eligibility-Model/ 
├── app.py 

├── train.py

├── Loan_Eligibility_Model_Solution.ipynb 

├── requirements.txt 

├── LICENSE  

├── README.md 

├── src/

   ├── ___init___.py
   
   ├── data_preprocessing.py
   
   ├── evaluate_model.py
   
   ├── logger.py
   
   ├── train_model.py
   
├── models/

   ├── loan_model.pkl
   
├── data/

   ├── credit.csv


## 💠 How to Use

1. Place your dataset as `loan_data.csv` in the `data/` folder.

2. Train the models:
   ```
   python train.py
   ```

3. Launch the Streamlit app:
   ```
   streamlit run app.py
   ```
### 🌐 Step 2: Set Up a Virtual Environment

python -m venv venv
source venv/bin/activate       # On Windows: venv\Scripts\activate

### 📦 Step 3: Install Dependencies

pip install -r requirements.txt

### ▶️ Step 4: Run the Streamlit App

streamlit run app.py

## 🎯 Features

Simple, interactive web interface using Streamlit

Predicts loan eligibility based on user inputs

Machine learning model trained on real-world dataset

Includes data preprocessing and feature engineering


---

## 🗃 Data

Gender, Marital Status, Dependents

Education Level, Employment Type

Applicant & Coapplicant Income

Loan Amount, Loan Term

Credit History, Property Area

Target: Loan_Status (Eligible or Not)

---

## 📈 Technologies Used

Python

Streamlit

Pandas, NumPy

Scikit-learn

---

## 🌩 Deployment

Local: http://localhost:8501/
Github: https://loaneligibilityapp-arjunvk.streamlit.app/

---

## 📜 License

Licensed under the [MIT License](LICENSE).

---

## 🙌 Contribution

Feel free to fork this repository and make improvements or adjustments. Pull requests and contributions are always welcome!

---

## ✉️ Contact

- **Author:** Arjun Vannathan Kandy
- **GitHub:** https://github.com/arjunvk007



