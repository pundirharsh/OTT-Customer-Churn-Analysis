# 📉 OTT Customer Churn Analysis

An end-to-end data analysis project that finds out why customers cancel their subscription on a streaming (OTT) platform, and which customers are likely to cancel next — using SQL and Python.

---

## 🎯 The Problem

Streaming platforms lose customers every month, and that costs real revenue. This project looks at customer, subscription, and support data together to figure out:

- How many customers are we losing, and how much money does that cost?
- Which plan and which region has the most cancellations?
- Do customer complaints lead to more cancellations?
- Who is likely to cancel next, so the business can reach out first?

## 🛠️ Tools Used

**Python** (Pandas, NumPy) · **SQL / SQLite** · **Matplotlib & Seaborn** · **Jupyter Notebook**

## 🔄 What I Did

1. **Pulled the data** — Connected Python to a SQL database and pulled three tables: customer info, subscriptions, and support tickets.
2. **Cleaned the data** — Fixed messy column names, removed columns I didn't need, corrected date formats, and filled in missing values.
3. **Created new columns**, such as:
   - Whether a customer cancelled or not
   - How long each customer stayed with the service
   - How many complaints each customer raised
   - A simple Low / Medium / High risk label per customer
4. **Combined everything** into one clean table so all three data sources could be analyzed together.
5. **Analyzed the numbers** — churn rate, revenue lost, average revenue per user, and more.
6. **Made charts** to see churn trends over time and spot patterns across plans and regions.
7. **Wrote up the findings** in plain language, along with what the business should do next.

## 📊 What I Found

- About **29%** of customers cancelled, and **71%** stayed.
- Most cancellations came from the **Basic plan** — cheaper customers, so not a huge revenue hit, but a clear warning sign.
- **Karnataka** had the most cancellations, and most of them happened in **September**.
- Customers on **monthly** plans cancel far more than customers on **yearly** plans (55.6% vs 8.3%).
- Customers who raise **support complaints** are more likely to cancel — more complaints, higher risk.
- Cancellations cost the company about **18% of total revenue**.


## ✅ What I'd Recommend Doing Next

- Find out what happened in Karnataka in September (price hike? bug? competitor offer?).
- Encourage monthly customers to switch to yearly plans — they cancel far less often.
- Reach out first to customers marked High or Medium risk, especially the high-value ones.
- Fix support issues faster, since complaints are a strong early warning sign of cancellation.

## 🗂️ About the Data

The dataset combines three sources for each customer:

- **Customer info** — demographics like age, gender, state, and country
- **Subscription details** — plan type (Basic/Standard/Premium), contract type (Monthly/Annual), monthly charges, start and cancellation dates
- **Support tickets** — number of complaints raised and whether they were escalated

These were joined together into a single dataset so patterns across all three areas could be analyzed at once.

## 🚀 How to Explore This Project

1. Read the **What I Found** and **Charts** sections above for a quick summary
2. Open `churn_analysis.ipynb` to see the full data cleaning, analysis, and chart-building process
3. Check `exported_churn_data.csv` for the final, cleaned dataset used in the analysis
4. Open `customer_churn.db` in any SQL tool to explore the raw source tables

## 👤 About Me

Aspiring Data Analyst with hands-on experience in Python, SQL, and data visualization, passionate about turning raw data into actionable business insights.

📧 Email: *add your email here*   🔗 LinkedIn: *add your LinkedIn here*   💻 Portfolio: *add your portfolio link here*
