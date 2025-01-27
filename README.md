# Zeotap-Tasks
Assignment
# eCommerce Transactions Dataset Analysis

This project focuses on analyzing an eCommerce transactions dataset consisting of customer, product, and transaction data. The goal is to perform exploratory data analysis (EDA), build predictive models, and generate business insights.

## Project Structure

- `Customers.csv`: Contains information about customers, such as their unique ID, name, region, and signup date.
- `Products.csv`: Contains product details including product ID, name, category, and price.
- `Transactions.csv`: Contains transaction information including transaction ID, customer ID, product ID, transaction date, quantity, total value, and price.

## Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights

1. Perform an in-depth EDA on the dataset to uncover hidden patterns and relationships.
2. Derive at least 5 actionable business insights from the EDA.
3. Provide the results in a PDF report.

**Deliverables:**
- Jupyter Notebook containing the EDA code.
- PDF report with business insights.

### Task 2: Lookalike Model

1. Build a Lookalike Model that identifies similar customers based on their profile and transaction history.
2. The model should provide a similarity score for each recommendation.
3. Output the top 3 lookalike customers for the first 20 customers and store the results in a CSV file.

**Deliverables:**
- Jupyter Notebook explaining the model development.
- `Lookalike.csv` containing the customer ID and their recommended lookalikes with similarity scores.

### Task 3: Customer Segmentation / Clustering

1. Perform customer segmentation using clustering techniques, considering both customer profiles and transaction data.
2. Choose an appropriate clustering algorithm and determine the optimal number of clusters.
3. Calculate clustering metrics, including the DB Index, and visualize the clusters.

**Deliverables:**
- Jupyter Notebook containing the clustering code.
- Report on clustering results, including metrics such as the DB Index value and visual representations of clusters.

## Installation

To run this project locally, make sure you have Python installed along with the following libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

You can install the required libraries using `pip`:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

Results will be saved in the corresponding output files (e.g., Lookalike.csv for Task 2).
