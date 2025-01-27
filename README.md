# Zeotap-Tasks
Assignment
eCommerce Transactions Dataset Analysis
This project focuses on analyzing an eCommerce transactions dataset consisting of customer, product, and transaction data. The goal is to perform exploratory data analysis (EDA), build predictive models, and generate business insights.

Project Structure
Customers.csv: Contains information about customers, such as their unique ID, name, region, and signup date.
Products.csv: Contains product details including product ID, name, category, and price.
Transactions.csv: Contains transaction information including transaction ID, customer ID, product ID, transaction date, quantity, total value, and price.
Tasks
Task 1: Exploratory Data Analysis (EDA) and Business Insights
Perform an in-depth EDA on the dataset to uncover hidden patterns and relationships.
Derive at least 5 actionable business insights from the EDA.
Provide the results in a PDF report.
Deliverables:

Jupyter Notebook containing the EDA code.
PDF report with business insights.
Task 2: Lookalike Model
Build a Lookalike Model that identifies similar customers based on their profile and transaction history.
The model should provide a similarity score for each recommendation.
Output the top 3 lookalike customers for the first 20 customers and store the results in a CSV file.
Deliverables:

Jupyter Notebook explaining the model development.
Lookalike.csv containing the customer ID and their recommended lookalikes with similarity scores.
Task 3: Customer Segmentation / Clustering
Perform customer segmentation using clustering techniques, considering both customer profiles and transaction data.
Choose an appropriate clustering algorithm and determine the optimal number of clusters.
Calculate clustering metrics, including the DB Index, and visualize the clusters.
Deliverables:

Jupyter Notebook containing the clustering code.
Report on clustering results, including metrics such as the DB Index value and visual representations of clusters.
Installation
To run this project locally, make sure you have Python installed along with the following libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn
You can install the required libraries using pip:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Usage
Clone the repository:
bash
Copy
Edit
git clone <repository_url>
Navigate to the project folder and open the Jupyter notebook or Python script for each task:
bash
Copy
Edit
cd <project_directory>
jupyter notebook
Notes
Ensure that the Customers.csv, Products.csv, and Transactions.csv files are available in the working directory for the scripts to function properly.
Each task is self-contained within its corresponding Jupyter notebook or Python script.
Results will be saved in the corresponding output files (e.g., Lookalike.csv for Task 2).
