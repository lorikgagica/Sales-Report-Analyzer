# 📈 Sales Report Analyzer (Python)

A complete command-line Python tool for analyzing and visualizing your sales data! Load your sales CSV, clean and preprocess it, and instantly get actionable insights and monthly visualizations.

---

## ✨ Features

- **Load sales data** from a CSV file (`sales_data.csv`)
- **Clean/preprocess data:**  
  - Fills missing product categories with `"Unknown"`
  - Drops rows with missing or invalid values
  - Converts dates and sales amounts to correct types
  - Adds useful columns (month, revenue)
- **Analyze:**  
  - Shows total sales by month  
  - Displays top 5 products by revenue
- **Plot:**  
  - Instantly visualize monthly sales with bar charts (matplotlib)
- **All steps are automated via one script**

---

## 🚀 How to Run

1. **Install requirements (Python 3, pandas, matplotlib):**
    ```
    pip install pandas matplotlib
    ```
2. **Save your CSV as `sales_data.csv`**
3. **Save the script as `sales.py`**
4. **Run the script in terminal:**
    ```
    python sales.py
    ```
5. **Follow the CLI prompts** — it will guide you through loading, cleaning, and analyzing the data.

---

## 🧑‍💻 Usage Example

- When prompted, enter the path to your sales data file (e.g., `sales_data.csv`)
- Script loads and cleans sales data (see preview and log messages)
- View sales statistics per month and top products
- Bar chart pops up for monthly sales (matplotlib)

---

## 🗂️ How It Works

- Loads CSV and converts columns for accurate analysis
- Cleans:
    - Fills missing product categories with `"Unknown"`
    - Drops rows with missing/invalid fields
    - Converts date and numeric columns properly
    - Computes additional columns like revenue and year/month
- Groups by month to sum total sales amount
- Identifies top 5 products by total revenue
- Visualizes monthly summary with a bar chart

---

## 📄 License

MIT License — free for learning, teaching, and tinkering.

---

A clean Python starter for anyone looking to extract instant insights from their sales data!
