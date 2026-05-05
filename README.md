![](https://images.pexels.com/photos/65882/chocolate-dark-coffee-confiserie-65882.jpeg)
<sup>[Pixabay](https://www.pexels.com/@pixabay) - pexels</sup>

## 🍫 Chocolate Sales Analytics & Forecasting

This project combines exploratory data analysis, machine learning forecasting, and Power BI dashboard to analyze chocolate sales across countries, products, and salespeople. Prediction of chocolate sales for the next year is made with Random Forest Regressor model[^1].

---

## Project Workflow

1. Clean and explore chocolate sales data in Python
2. Train a Random Forest Regressor to predict future sales
3. Export 2025 sales predictions to CSV
4. Build an interactive Power BI dashboard
5. Compare historical performance and predicted sales

---

## Data
Data came from [this dataset](https://www.kaggle.com/datasets/saidaminsaidaxmadov/chocolate-sales).
The dataset represents a global chocolate company tracking sales performance across products, countries, and employees. 

---

## How to work with chocolate_sales repository:
1. Clone the repository with:\
 bash
 ```
 git clone https://github.com/lmacakova/chocolate_sales.git
 cd chocolate_sales
 ```
2. Create a virtual environment:\
 bash
 ```
 python -m venv .venv
 ```
    # macOS/Linux
 ```
 source .venv/bin/activate
 ```
    # Windows PowerShell
 ```
 .venv\Scripts\Activate.ps1
 ```
3. Install requirements:\
 bash
 ```
 pip install --upgrade pip
 pip install -r requirements.txt
 ```
4. Open the notebook in VS Code or Visual Studio Code and select Python (applied) as the kernel. Open the dashboard in Power BI.


---

[^1]:  https://en.wikipedia.org/wiki/Random_forest