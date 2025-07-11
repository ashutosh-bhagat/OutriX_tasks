# E-Commerce Data Analysis Project

## 📊 Overview
This project performs comprehensive analysis of E-Commerce transaction data to uncover insights about customer behavior, product performance, and business metrics.

## 📁 Project Structure
```
E-Commerce/
├── analyse.ipynb          # Main analysis notebook
├── ecommerce.csv          # Dataset (250K records, 21MB)
├── requirements.txt       # Python dependencies
└── README.md             # This file
```

## 🎯 Key Insights from Analysis

### Customer Demographics
- **Gender Distribution**: Analyzed customer gender ratios with bar and pie charts
- **Age Groups**: Segmented customers into age brackets (0-20, 21-30, 31-40, 41-50, 51-60, 61-70)
- **Age vs Purchase Patterns**: Line chart showing purchase amounts by age group and gender

### Product Performance
- **Category Analysis**: Horizontal bar chart of most purchased product categories
- **Returns Analysis**: Pie chart showing return rates by product category
- **Top Categories**: Identified best and worst performing product categories

### Payment & Transaction Analysis
- **Payment Methods**: Distribution analysis of different payment options
- **Gender vs Payment**: Stacked bar chart showing payment preferences by gender
- **Transaction Metrics**: Total sales, average purchase amounts, return rates

### Business Metrics Dashboard
- Total Sales Revenue
- Total Returns Count
- Average Purchase Amount
- Top Product Categories by Sales
- Most Returned Categories
- Popular Payment Methods

## 🛠️ Technical Details

### Dataset Information
- **Size**: 250,000 records
- **Columns**: 13 features including Customer ID, Purchase Date, Product Category, Price, Quantity, Payment Method, Age, Gender, Returns, etc.
- **Data Types**: Mix of numerical and categorical data

### Analysis Techniques Used
- **Data Visualization**: Matplotlib, Seaborn
- **Data Manipulation**: Pandas
- **Statistical Analysis**: NumPy
- **Chart Types**: Bar charts, pie charts, line charts, stacked bar charts

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook or JupyterLab

### Installation
1. Clone or download this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `analyse.ipynb` in Jupyter Notebook
4. Run all cells to reproduce the analysis

## 📈 Key Findings
- Gender distribution patterns in customer base
- Age group purchasing behavior differences
- Product category performance rankings
- Payment method preferences by demographic
- Return rate analysis by product category
- Overall business performance metrics

## 🔧 Dependencies
See `requirements.txt` for complete list of Python packages used in this analysis.

## 📝 Usage
1. Ensure the `ecommerce.csv` file is in the same directory as the notebook
2. Run the notebook cells sequentially
3. All visualizations will be displayed inline
4. The final dashboard provides a comprehensive business overview

## 📊 Output
The analysis generates multiple visualizations including:
- Gender distribution charts
- Payment method analysis
- Product category performance
- Age-based purchase patterns
- Return analysis
- Comprehensive business dashboard

---
*This project demonstrates comprehensive E-Commerce data analysis using Python data science tools.* 