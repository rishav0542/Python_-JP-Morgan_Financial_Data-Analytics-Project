# Python_-JP-Morgan_Financial_Data-Analytics-Project

<h1 align="center">Hi 👋, I'm Rishav Singh</h1>
<h3 align="center">A passionate data analyst trainee from India</h3>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=rishav0542&label=Profile%20views&color=0e75b6&style=flat" alt="rishav0542" /> </p>


- 🔭 I’m currently working on **Data Analytics Projects**

- 🌱 I’m currently learning **Data Science and it's core domain**

- 💬 Ask me about **Data and insights!**

- 📫 How to reach me **singh.rishav086@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/https://www.linkedin.com/in/rishav-singh-11720b298/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/rishav-singh-11720b298/" height="30" width="40" /></a>
<a href="https://www.topcoder.com/members/221005" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/topcoder.svg" alt="221005" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> </p>

# JP Morgan Financial Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-00A3E0?style=for-the-badge)

**A complete end-to-end financial transaction analysis** on JP Morgan banking data (800 records).  
Includes data cleaning, descriptive analytics, customer profiling, segmentation, statistical testing, and professional visualizations.

**[Watch Project Walkthrough Video](https://www.loom.com/share/59e65e2576c44e5ca21f848147ab43a4)**

---

## 📋 Project Highlights

- **Data Cleaning & Standardization** – Fixed column names, standardized signs (Deposit/Transfer = +ve, Withdrawal/Payment = –ve), date formatting, rounding
- **Descriptive Transactional Analysis** – Monthly & yearly credit/debit/net volume summaries
- **Trends Visualization** – Credits vs Debits over time
- **Account Performance** – Top 10 & Bottom 10 accounts by net inflow
- **Dormant Account Detection** – Flagged accounts inactive for ≥2 months (84.54% dormant)
- **Customer Profiling** – Activity Level segmentation (High/Medium/Low)
- **Advanced Segmentation** – Volume segments (High/Low) & Balance segments
- **Hypothesis Testing** (SciPy)  
  - High vs Low volume accounts balance → **No significant difference**  
  - Medium vs Low activity accounts balance → **No significant difference**
- **Risk vs Credit Rating Analysis** – Scatter plot + correlation insight

---

## 📊 Key Visualizations

### 1. Transactions by Type
![Transactions by Type](images/txn_type.png)

### 2. Distribution of Account Balances
![Distribution of Account Balances](images/bal_dist.png)

### 3. Distribution of Transaction Amounts
![Distribution of Transaction Amounts](images/txn_dist.png)

### 4. Average Balance by Region
![Average Balance by Region](images/bal_region.png)

### 5. Risk Score vs Credit Rating
![Risk Score vs Credit Rating](images/risk_credit.png)
*Insight: Almost zero linear correlation – Risk Score is not a strong predictor of Credit Rating.*

### 6. Monthly Trends – Credits vs Debits
![Trends in Credits vs Debits](images/trends.png)

---

📌 Key Insights

1.No statistically significant difference in balances between High/Low volume accounts or Medium/Low activity levels.

2.84.54% accounts are dormant.

3.Transaction signs properly standardized (+ve inflow / –ve outflow).

4.Clear regional balance patterns and transaction distributions.

## 🛠 Technologies Used

- Python 3.13
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy (ttest_ind)
- Jupyter Notebook

---

## 📁 Project Structure



