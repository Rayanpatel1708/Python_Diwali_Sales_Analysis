# Python_Diwali_Sales_Analysis
 # 🪔 Diwali Sales Analysis using Python

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0?style=for-the-badge)

---

## 📌 Project Overview

This project performs an **Exploratory Data Analysis (EDA)** on Diwali sales data to uncover meaningful insights about customer purchasing behavior during India's biggest festive season.

The goal is to help businesses:
- Understand their **target customer segments**
- Identify **top-performing product categories**
- Make **data-driven decisions** to boost sales and improve customer experience

---

## 🎯 Objectives

- Analyze customer demographics (gender, age group, marital status, occupation, state)
- Identify the most profitable product categories and top-selling products
- Understand regional sales distribution across Indian states
- Provide actionable insights for marketing and inventory planning

---

## 📂 Project Structure

```
Python_Diwali_Sales_Analysis/
│
├── Diwali Sales Analysis.ipynb    # Main Jupyter Notebook with full analysis
├── Diwali Sales Data.csv          # Dataset used for analysis
└── README.md                      # Project documentation
```

---

## 📊 Dataset Description

The dataset contains **11,251 records** with the following key columns:

| Column | Description |
|---|---|
| `User_ID` | Unique customer identifier |
| `Cust_name` | Customer name |
| `Product_ID` | Unique product identifier |
| `Gender` | Gender of the customer |
| `Age Group` | Age bracket of the customer |
| `Age` | Exact age |
| `Marital_Status` | 0 = Unmarried, 1 = Married |
| `State` | Indian state of the customer |
| `Zone` | Geographic zone (North/South/East/West/Central) |
| `Occupation` | Customer's profession |
| `Product_Category` | Category of the purchased product |
| `Orders` | Number of orders placed |
| `Amount` | Total purchase amount (₹) |

---

## 🔍 Analysis Performed

### 1. 🧹 Data Cleaning & Preprocessing
- Dropped null values and irrelevant columns
- Fixed data types (e.g., `Amount` to integer)
- Handled missing/duplicate entries

### 2. 📈 Exploratory Data Analysis (EDA)

#### Gender Analysis
- Females are the **majority of buyers** and have **higher purchasing power** than males

#### Age Group Analysis
- The **26–35 age group** (especially females) contributes the **most to total sales (~40%)**

#### State-wise Analysis
- Top states by orders and revenue: **Uttar Pradesh, Maharashtra, and Karnataka**

#### Marital Status Analysis
- **Married women** show strong purchasing potential with higher average spending

#### Occupation Analysis
- Buyers from **IT, Healthcare, and Aviation** sectors are the biggest spenders

#### Product Category Analysis
- Top categories: **Food, Clothing & Apparel, and Electronics**
- Food leads in revenue; Clothing leads in number of orders

---

## 💡 Key Insights & Findings

> 🎯 **Most likely Diwali buyer:** Married women aged 26–35, from UP/Maharashtra/Karnataka, working in IT, Healthcare, or Aviation — purchasing Food, Clothing, or Electronics.

- 📍 Focus marketing campaigns on **UP, Maharashtra & Karnataka**
- 👩 Tailor product promotions towards the **female demographic**
- 🛒 Stock up on **Food, Electronics & Clothing** before the festive season
- 💼 Target **IT & Healthcare professionals** with premium offerings

---

## 🛠️ Technologies Used

| Tool | Purpose |
|---|---|
| **Python 3.x** | Core programming language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computations |
| **Matplotlib** | Data visualization (bar charts, count plots) |
| **Seaborn** | Statistical data visualization |
| **Jupyter Notebook** | Interactive development environment |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8+ installed. Then install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Running the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/Rayanpatel1708/Python_Diwali_Sales_Analysis.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd Python_Diwali_Sales_Analysis
   ```

3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Open** `Diwali Sales Analysis.ipynb` and run the cells sequentially

---

## 📸 Sample Visualizations

The notebook includes the following charts:
- 📊 Count plots for Gender, Age Group, and Marital Status
- 📊 Bar charts for State-wise Orders and Revenue
- 📊 Occupation-wise and Product Category-wise sales
- 📊 Top 10 most sold Products

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👤 Author

**Rayan Patel**  
📧 [GitHub Profile](https://github.com/Rayanpatel1708)

---

> ⭐ If you found this project helpful, please give it a **star** on GitHub!
