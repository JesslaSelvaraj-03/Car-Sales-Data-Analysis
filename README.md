# Car-Sales-Data-Analysis
Comprehensive Car Sales Data Analysis project using Python, Pandas, NumPy, Matplotlib, and Seaborn. Covers data cleaning, handling nulls, removing duplicates, and performing EDA with visual insights on brand performance, pricing trends, fuel type distribution, and sales patterns across regions and years.

## 📘 Project Overview
This project analyzes a **car sales dataset** to generate **actionable business insights** about sales trends, popular car brands, pricing, and regional performance.  
It demonstrates the complete process of **data cleaning**, **exploratory data analysis (EDA)**, and **data visualization** using Python libraries such as **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**.

---

## 📊 Dataset Information

**File Name:** `cars_dataset.csv`  
**Shape:** `(1200, 10)`  

| Column Name      | Description |
|------------------|-------------|
| `Car_ID`         | Unique identifier for each car |
| `Brand`          | Brand name of the car (e.g., Maruti, Hyundai, Honda) |
| `Model`          | Model name of the car |
| `Year`           | Year of manufacture |
| `Fuel_Type`      | Type of fuel used (Petrol, Diesel, CNG, etc.) |
| `Transmission`   | Transmission type (Manual / Automatic) |
| `Kms_Driven`     | Total kilometers driven |
| `Present_Price`  | Current market price of the car |
| `Selling_Price`  | Actual selling price of the car |
| `Region`         | Region where the car was sold |

---

## ⚙️ Data Preprocessing Steps

1. **Load the dataset** using Pandas  
2. **Display basic details:**
   - First and last few records  
   - Shape, columns, and data types  
3. **Handle missing values:**
   - Numeric columns → fill with **median**  
   - Categorical columns → fill with **mode**  
4. **Remove duplicate rows** (if any)  
5. **Convert column data types** if necessary  
6. **Save the cleaned dataset** as `cleaned_cars_dataset.csv`

---

## 📈 Exploratory Data Analysis (EDA)

The EDA phase involves summarizing and analyzing the dataset to understand trends and relationships.

- Summary statistics (mean, median, mode, std deviation)
- Number of cars sold per brand
- Average selling price per brand and per fuel type
- Top 5 most sold car models
- Correlation between `Selling_Price` and numerical features such as `Kms_Driven`, `Year`, etc.

---

## 🎨 Data Visualization

Visual insights are created using **Matplotlib** and **Seaborn** for better understanding of data patterns.

| Visualization | Description |
|----------------|--------------|
| **Bar Chart** | Number of cars sold per brand |
| **Pie Chart** | Fuel type distribution |
| **Line Chart** | Sales trend by year |
| **Box Plot** | Selling price vs fuel type |
| **Scatter Plot** | Present price vs selling price |

---

## 🧰 Tools & Technologies

| Tool | Purpose |
|------|----------|
| **Python** | Core programming language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computations |
| **Matplotlib** | Visualization library |
| **Seaborn** | Advanced statistical plotting |

---

## 🧠 Insights You Can Derive

- Which **brands** have the highest car sales  
- The most popular **fuel type** among buyers  
- Which **models** retain high resale value  
- Impact of **car age (Year)** on selling price  
- Relationship between **Present Price**, **Kms Driven**, and **Selling Price**

---

## 📂 Project Structure

Car_Sales_Analysis/
│
├── cars_dataset.csv # Original dataset
├── cleaned_cars_dataset.csv # Cleaned dataset (after preprocessing)
├── cars_analysis.ipynb # Jupyter Notebook (analysis code)
└── README.md # Project documentation

yaml
Copy code

---

## 🧩 How to Run the Project

### 🔹 Step 1: Clone or Download the Repository
```bash
git clone https://github.com/YourGitHubUsername/Car-Sales-Analysis.git
cd Car-Sales-Analysis
🔹 Step 2: Install Required Libraries
Make sure you have Python installed (3.8+).
Then install the dependencies:

bash
Copy code
pip install pandas numpy matplotlib seaborn
🔹 Step 3: Run the Project
If using Jupyter Notebook:

bash
Copy code
jupyter notebook cars_analysis.ipynb
If using Python Script:

bash
Copy code
python cars_analysis.py
📊 Sample Output Visuals
Chart	Description
Cars sold per brand
Fuel type distribution
Sales trend by year

💾 Output Files
File	Description
cleaned_cars_dataset.csv	Cleaned dataset after removing nulls & duplicates
cars_analysis.ipynb / .py	Source code for data cleaning, analysis, and visualization
README.md	Documentation for project setup and explanation

🏁 Conclusion
This project demonstrates a complete data analysis pipeline — from data cleaning to insightful visualizations.
It helps identify market trends, brand performance, and price patterns, which can guide better business decisions in the automobile sector.
