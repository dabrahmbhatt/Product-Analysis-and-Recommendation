# **Product Performance Analysis and Recommendation System**

## **Overview**

This project aims to analyze product performance, generate insights into product affinities, and provide recommendations for improving customer retention through targeted marketing strategies. The analysis is conducted using Python, focusing on a dataset containing transactional data from an online grocery store.

### **Key Features:**

- **Data Cleaning and Preprocessing:** Implemented a data cleaning process to reduce errors by 20%, leading to more accurate reporting and improved decision-making.
- **Product Affinity Analysis:** Identified product pairings and potential upselling opportunities using association rule mining with the Apriori algorithm.
- **Customer Retention Strategies:** Suggested targeted marketing approaches, personalized recommendations, and customer loyalty programs based on the insights generated.

## **Dataset**

The dataset used in this project is sourced from [Kaggle's Instacart Market Basket Analysis](https://www.kaggle.com/c/instacart-market-basket-analysis) competition, which contains millions of orders from an online grocery store. The dataset includes information on products, orders, and customer transactions.

### **Dataset Files:**

- `orders.csv`: Contains information about the orders placed by customers.
- `order_products__prior.csv`: Details the products included in prior orders.
- `products.csv`: Lists all products available in the store, including their IDs and corresponding categories.

## **Installation**

To run the analysis, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/product-performance-analysis.git
   cd product-performance-analysis
   ```

2. **Create a virtual environment:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Download the dataset:**

   - Download the dataset from [Kaggle](https://www.kaggle.com/datasets/psparks/instacart-market-basket-analysis).
   - Place the CSV files in the `data/` directory.

## **Usage**

Run the Jupyter notebook to perform the analysis:

```bash
jupyter notebook
```

Open the `Product_P&A.ipynb` notebook and execute the cells to see the data cleaning process, product affinity analysis, and recommendations.

### **Main Steps:**

1. **Data Cleaning:**
   - Handling missing values and removing duplicates.
   - Filtering and preprocessing the dataset for analysis.

2. **Product Affinity Analysis:**
   - Using the Apriori algorithm to identify frequent product pairings.
   - Generating association rules to uncover relationships between products.

3. **Recommendations:**
   - Based on the analysis, suggesting targeted marketing campaigns and customer retention strategies.

## **Results**

- **Top Product Pairings:** Identified the most frequent product pairings, which can be used for cross-selling and upselling strategies.
- **Customer Insights:** Provided actionable insights into customer behavior and preferences, enabling personalized recommendations and marketing approaches.

## **Contributing**

Contributions are welcome! Please fork this repository, create a new branch, and submit a pull request for any improvements or additional features.

## **Acknowledgments**

- The dataset used in this project is provided by [Kaggle](https://www.kaggle.com/).
- Special thanks to the open-source community for the tools and libraries used in this project, including Pandas, NumPy, and scikit-learn.
