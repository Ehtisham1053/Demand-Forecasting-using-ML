# Demand-Forecasting-using-ML

# Data Analysis Project

## 📌 Project Overview
This repository contains a Jupyter Notebook (`.ipynb`) that performs data analysis on a retail sales dataset. The analysis includes data preprocessing, exploratory data analysis (EDA), visualization, and statistical insights.



## 📊 Dataset Information
The dataset consists of multiple files related to retail sales, stores, transactions, holidays, and oil prices.

### 📁 Datasets and Features
#### **1. Train Dataset** (`train.csv`)
- `id`: Unique identifier
- `date`: Date of transaction
- `store_nbr`: Store number
- `family`: Product family
- `sales`: Number of sales
- `onpromotion`: Number of items on promotion
- `dayofweek`: Day of the week
- `year`: Year of transaction

#### **2. Stores Dataset** (`stores.csv`)
- `store_nbr`: Store number (unique identifier)
- `city`: City where the store is located
- `state`: State where the store is located
- `type`: Store type
- `cluster`: Store cluster category

#### **3. Transactions Dataset** (`transactions.csv`)
- `date`: Date of transaction
- `store_nbr`: Store number
- `transactions`: Total number of transactions for that store and date

#### **4. Holidays Dataset** (`holidays.csv`)
- `date`: Date of the holiday
- `holiday_type`: Type of holiday (e.g., National, Local, Regional)
- `locale`: Scope of the holiday (e.g., National, Local)
- `locale_name`: Name of the affected location
- `description`: Holiday description
- `transferred`: Indicates if the holiday was transferred to another date

#### **5. Oil Prices Dataset** (`oil.csv`)
- `date`: Date
- `oil_price`: Price of oil on that date

## 🔧 Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/data-analysis-project.git
   cd data-analysis-project
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook analysis.ipynb
   ```

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📌 Example Usage in Jupyter Notebook
Load and clean the dataset in a Jupyter Notebook cell:
```python
import pandas as pd

# Load datasets
df_train = pd.read_csv("data/train.csv")
df_stores = pd.read_csv("data/stores.csv")
df_transactions = pd.read_csv("data/transactions.csv")
df_holidays = pd.read_csv("data/holidays.csv")
df_oil = pd.read_csv("data/oil.csv")

# Display first few rows
df_train.head()
```

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📞 Contact
For any questions or suggestions, reach out to:
- **Your Name**
- Email: [2020n08248@gmail.com](mailto:your.email@example.com)
- GitHub: [Ehtisham1053](https://github.com/yourusername)
