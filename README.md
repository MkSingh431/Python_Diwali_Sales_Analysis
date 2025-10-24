![Diwali Festival](https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=1200&q=80)

# Diwali Sales Analysis

## 📌 Project Overview
A professional data analysis project exploring sales trends during the Diwali festival. The project uses Python and industry-standard libraries to clean, process, and visualize sales data, delivering actionable business insights.

## 🗂 Dataset
The dataset includes:
- Customer demographics (Gender, Age Group, State, Marital Status, Occupation)
- Product categories and product IDs
- Purchase amounts and number of orders
- Payment methods

## 🛠 Technologies Used
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

## 📝 Step-by-Step Analysis Workflow

### 1. Data Loading
- Import libraries and load the Diwali sales CSV file using pandas.

### 2. Data Cleaning & Preprocessing
- Remove unrelated or blank columns (`Status`, `unnamed1`).
- Check for and handle missing values.
- Convert `Amount` column to integer type.
- Rename columns for clarity (e.g., `Marital_Status` to `Shaadi`).

### 3. Data Exploration
- Use `.info()` and `.describe()` for data structure and summary statistics.
- Explore key columns (`Age`, `Orders`, `Amount`) for deeper insights.

### 4. Exploratory Data Analysis (EDA)
#### Gender Analysis
- Countplot for gender distribution.
- Barplot for total amount by gender.
- **Insight:** Females are the majority buyers and have higher purchasing power.

#### Age Group Analysis
- Countplot for age group distribution (with gender hue).
- Barplot for total amount by age group.
- **Insight:** Females aged 26-35 are the most active buyers.

#### State Analysis
- Barplot for top 10 states by number of orders and sales amount.
- **Insight:** Uttar Pradesh, Maharashtra, and Karnataka are top contributors.

#### Marital Status Analysis
- Countplot for marital status.
- Barplot for total amount by marital status and gender.
- **Insight:** Married women show high purchasing power.

#### Occupation Analysis
- Countplot for occupation distribution.
- Barplot for total amount by occupation.
- **Insight:** IT, Healthcare, and Aviation professionals are most active buyers.

#### Product Category Analysis
- Countplot for product category distribution.
- Barplot for top 10 product categories by sales amount.
- Barplot for top 10 products by number of orders.
- **Insight:** Food, Clothing, and Electronics are most popular categories.

### 5. Visualization
- All plots are generated using matplotlib and seaborn for professional presentation.

### 6. Conclusion & Recommendations
- Females aged 26-35, especially married women, are the primary buyers.
- Focus marketing on top states and popular product categories.
- Target professionals in IT, Healthcare, and Aviation.
- Optimize inventory and promotions based on state and occupation analysis.

### 7. References & Project Link
- [Complete project on GitHub](https://github.com/MkSingh431/Python_Diwali_Sales_Analysis)

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/MkSingh431/Python_Diwali_Sales_Analysis.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Python_Diwali_Sales_Analysis-main
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
5. Run the analysis notebook to view insights and visualizations.

## 📈 Key Findings
- Females aged 26-35, especially married
## 📈 Key Findings
- Most buyers are females aged 26-35, especially married women
- Highest sales from Uttar Pradesh, Maharashtra, and Karnataka
- IT, Healthcare, and Aviation professionals are top buyers
- Food, Clothing, and Electronics are the most purchased categories

## 📌 Future Enhancements
- Predictive modeling for sales forecasting
- Interactive dashboards using Power BI, Tableau, or Plotly Dash
- Customer segmentation and personalized marketing

## 🤝 Contributing
Feel free to contribute by opening issues or submitting pull requests.

## 📜 License
This project is licensed under the MIT License.

---

## 🔗 Author & Contact
- [Motilal Das on LinkedIn](https://www.linkedin.com/in/motilal-das-42b4a9254)

📩 For any queries, feel free to reach out!

