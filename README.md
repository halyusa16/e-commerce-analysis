# e-commerce-analysis
This self-project analyzes a public e-commerce dataset to extract valuable insights and answer critical business questions, such as sales trends, product performance, payment preferences, and customer reviews.

## **Overview**
This project analyzes a public e-commerce dataset to uncover valuable insights and answer critical business questions. The dataset contains customer, product, order, and transaction details, providing a comprehensive view of the e-commerce platform's operations.

## **Objectives**
The primary objectives of this project include:
1. Analyzing monthly sales trends.
2. Identifying best-selling and least-selling products.
3. Understanding customer payment preferences.
4. Evaluating customer review distributions.

## **Dataset**
The dataset consists of multiple CSV files, each representing a specific aspect of the e-commerce business:
- `customers_dataset.csv`: Customer demographics.
- `geolocation_dataset.csv`: Customer location details.
- `order_items_dataset.csv`: Details of items in each order.
- `order_payments_dataset.csv`: Payment methods and values.
- `order_reviews_dataset.csv`: Customer reviews and scores.
- `orders_dataset.csv`: Order statuses and timestamps.
- `products_dataset.csv`: Product information.
- `product_category_name_translation.csv`: Translations for product categories.
- `sellers_dataset.csv`: Seller details.

## **Key Insights**
1. **Sales Trends:**
   - Monthly sales increased significantly from December 2016, peaking in November 2017 with sales exceeding $1M.
2. **Top-Selling Products:**
   - Categories like `bed_bath_table` and `health_beauty` were the most popular.
   - Least sold categories included niche items like `fashion_bags` and `security`.
3. **Payment Preferences:**
   - Credit card usage dominated, accounting for 75.2% of all transactions, followed by boleto (bank slips).
4. **Customer Reviews:**
   - Majority of customers rated their experience 5 stars, indicating high satisfaction levels.

## **Process**
### 1. **Data Wrangling**
- Uploaded and inspected each dataset.
- Cleaned missing values and handled duplicates.
- Standardized data types for consistency.

### 2. **Exploratory Data Analysis (EDA)**
- Conducted analysis to uncover patterns in sales, customer behavior, and payment methods.
- Merged datasets to derive meaningful insights.
- Used visualizations for trend analysis and distribution comparisons.

### 3. **Data Visualization**
- Created charts to depict monthly sales trends, payment distributions, product performance, and customer review scores.

## **Technologies Used**
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Tools:** Jupyter Notebook
