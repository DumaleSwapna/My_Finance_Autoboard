
# 💰 My Finance Auto Board 

A simple yet powerful personal finance tracking dashboard built with **Streamlit**. This app allows you to upload your bank transaction CSV files, categorize your expenses and income, and gain insights into your financial habits — all in an interactive and visual format.

---

## 🚀 Features

- 📂 Upload your transaction CSV file
- 🧹 Automatic data cleaning (removes commas, parses dates, converts amounts)
- 📊 Split transactions into **Debits (Expenses)** and **Credits (Payments)**
- 🗂️ Add custom categories and automatically categorize transactions
- 💾 Save and load categories using a local JSON file
- 🔎 Categorize based on keywords in the transaction details
- 🖥️ Simple, responsive UI with tabs using Streamlit

---

## 🧠 How It Works

1. **Upload File:** You upload a CSV file with columns like `Date`, `Amount`, `Details`, and `Debit/Credit`.
2. **Data Processing:**
   - Spaces are removed from column names
   - Amounts are converted to float
   - Dates are parsed properly
3. **Categorization:**
   - A JSON file stores categories and keywords
   - Transactions are categorized based on keywords found in the "Details" column
4. **UI Tabs:**
   - "Expenses (Debits)" tab shows your spending
   - "Payments (Credits)" tab shows your incoming money
   - You can create new categories dynamically

----

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – UI and interactivity
- **Pandas** – Data processing
- **Plotly (Coming Soon)** – Visualizations
- **JSON** – Category storage

----



