# Artificial-Neural-Network-ANN-

# 🧠 Customer Churn Prediction using ANN  

This project implements an **Artificial Neural Network (ANN)** to predict whether a bank customer will churn (leave the bank) or stay.<br>
The model is trained on the **Churn Modelling dataset** using preprocessing and feature scaling techniques to improve prediction accuracy.<br>

---

# 📊 Dataset  

**Churn_Modelling.csv**  

Features used in the model:<br>

- CreditScore  
- Geography  
- Gender  
- Age  
- Tenure  
- Balance  
- NumOfProducts  
- HasCrCard  
- IsActiveMember  
- EstimatedSalary  

**Target:**  
- Exited → 0 = Stay, 1 = Churn  

---

# ⚙️ Data Preprocessing  

The following preprocessing steps were applied:<br>

- Geography encoding → France = 0, Spain = 1, Germany = 2  
- Gender encoding → Female = 0, Male = 1  
- Feature Scaling → StandardScaler  
- Train-Test Split → 80% / 20%  

---

# 🧠 ANN Model Architecture  

- Input Layer → 10 features  
- Hidden Layer 1 → Dense(16, ReLU)  
- Hidden Layer 2 → Dense(8, ReLU)  
- Output Layer → Dense(1, Sigmoid)  

**Loss Function:** Binary Crossentropy<br>
**Optimizer:** Adam  


# 🚀 Model Training  

The ANN model was trained to classify customers into:<br>

- **0 → Customer stays**  
- **1 → Customer churns**  

---

# 🧪 User Input Prediction  

The notebook allows manual user input to predict churn for a new customer.<br>

**Example Input:**  
Credit Score: 650 <br>
Geography: France <br>
Gender: Male <br>
Age: 40 <br>
Tenure: 5 <br>
Balance: 60000 <br>
Num Of Products: 2 <br>
Has Credit Card: 1 <br>
Is Active Member: 1 <br>
Estimated Salary: 50000 <br>


**Output:**  

Customer likely to STAY  <br>
---

# 📈 Applications  

- Customer retention strategy  
- Banking analytics  
- Risk assessment  
- Marketing targeting  

---

# 🛠️ Technologies Used  

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Jupyter Notebook  

---

 # ✅ Conclusion  

This project demonstrates how Artificial Neural Networks can be applied to structured banking data to predict customer churn and support business decision-making.<br>


