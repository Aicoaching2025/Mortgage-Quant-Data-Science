
### **📌 Mortgage Prepayment & Default Risk Modeling**
#### **A Data-Driven Approach for Front Office Mortgage Trading & Risk Management**
  
📊 **Author:** Candsace Grant
📅 Date:March 17th, 2025
🚀 GitHub Repository: aicoaching2025@github.com

---

## **📖 Overview**
This project builds **machine learning models** to predict **mortgage prepayment and default risks**, assisting the **Front Office Mortgage Quant team** in **pricing, hedging, and risk management** for **Residential Mortgage-Backed Securities (RMBS)** and **Commercial Mortgage-Backed Securities (CMBS)**.  

📌 **Key Features:**  
✅ **Predicts prepayment & default probabilities** for mortgage loans  
✅ **Monte Carlo simulations** to analyze interest rate impacts  
✅ **Interactive dashboard for traders** to assess loan risk in real time  
✅ **Data-driven pricing insights** for MBS trading & risk mitigation  

---

## **🎯 Business Use Case**
Mortgage-backed securities (MBS) involve **prepayment risk** (borrowers paying early) and **default risk** (loan non-payment). These risks impact:  
- **Traders** who price and hedge mortgage portfolios  
- **Risk managers** monitoring portfolio exposure  
- **Senior leadership** making capital allocation decisions  

🔍 **Objective:**  
- Provide a **data-driven solution** to quantify and predict these risks  
- Assist traders with **real-time analytics** for deal structuring  
- Improve **hedging strategies** for market volatility  

---

## **🔧 Technologies Used**
| Tool | Purpose |
|------|---------|
| **Python** | Core programming |
| **Pandas / NumPy** | Data manipulation |
| **XGBoost / Random Forest** | Prepayment & default prediction |
| **Monte Carlo Simulation** | Interest rate shock analysis |
| **Matplotlib / Seaborn / Plotly** | Data visualization |
| **Lifelines (Survival Analysis)** | Default risk modeling |
| **Flask / Streamlit** | Interactive trader dashboard |

---

## **📊 Data & Features**
**🔹 Dataset:**  
- **Fannie Mae Loan Performance Data** (Public Data)  
- **Macroeconomic Indicators (FRED API)**  
- **Interest Rate & Yield Curve Data (Bloomberg API)**  

**🔹 Key Features:**
| Feature | Description |
|---------|-------------|
| **Loan Age** | Months since mortgage originated |
| **Loan-to-Value (LTV)** | Loan amount vs. property value |
| **Borrower Credit Score** | FICO score indicating creditworthiness |
| **Interest Rate** | Current loan interest rate |
| **Remaining Term** | Months left for full repayment |
| **Delinquency Status** | Whether borrower has missed payments |

---

## **🛠️ Implementation**
### **📌 Step 1: Data Cleaning & Feature Engineering**
- Handle **missing values**
- Convert **categorical data**
- Engineer **time-series risk metrics**  

### **📌 Step 2: Machine Learning Modeling**
✅ **Prepayment Model:** XGBoost (Gradient Boosting Classifier)  
✅ **Default Model:** Random Forest + Survival Analysis  
✅ **Evaluation Metrics:** Accuracy, AUC-ROC, RMSE  

### **📌 Step 3: Monte Carlo Simulation for Risk Hedging**
Simulates **1,000 interest rate shocks** to analyze:  
- 📈 **Prepayment probability shifts**  
- 📉 **Default rate fluctuations**  
- 📊 **Risk-adjusted pricing insights**  

### **📌 Step 4: Interactive Dashboard for Traders**
Built with **Streamlit**, this dashboard allows traders to:  
✅ **Input loan details**  
✅ **View real-time risk predictions**  
✅ **Analyze impact of market shocks**  

---

## **📊 Results & Insights**
✅ **Prepayment increases when interest rates drop**  
✅ **Default risk rises with lower credit scores & higher LTV ratios**  
✅ **Monte Carlo simulations provide actionable hedging strategies**  
✅ **Trader dashboard enables real-time decision-making**  

---

## **🚀 How to Run the Project**
### **1️⃣ Install Dependencies**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost lifelines streamlit plotly joblib
```
### **2️⃣ Train & Save Models**
```python
import joblib
joblib.dump(xgb_prepay, "prepayment_model.joblib")
joblib.dump(rf_default, "default_model.joblib")
```
### **3️⃣ Run Streamlit Dashboard**
```bash
streamlit run app.py
```
---

## **📌 Why This Project Stands Out for a Mortgage Quant Role**
🔹 **Solves a real-world mortgage trading problem**  
🔹 **Combines machine learning & financial modeling**  
🔹 **Uses Monte Carlo simulations for risk mitigation**  
🔹 **Delivers real-time analytics for traders**  
🔹 **Showcases Python, financial modeling, & risk management skills**  

---

## **📬 Contact & Next Steps**
💡 Want to discuss this project further? Connect with me on [LinkedIn](#) or check out my [GitHub](#) for more financial analytics projects.  

---

## **⭐ Next Steps**
- **Enhance prediction accuracy** with deep learning (LSTMs for time series)  
- **Integrate real-time market data** (Bloomberg API)  
- **Expand risk metrics** to include stress testing  

---

📌 **If you find this project useful, give it a ⭐ on GitHub!**  

