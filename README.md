# End-to-End Data Analytics Project  

This repository contains an **end-to-end data analytics project** that utilizes Python and SQL to process and analyze data. The goal is to demonstrate the complete lifecycle of a data analytics workflow, from dataset acquisition to answering key business questions.

---

## Project Overview  
### Steps:
1. **Dataset Acquisition**  
   - Use the Kaggle API to programmatically download the dataset.

2. **Data Processing and Cleaning**  
   - Use **Pandas** for cleaning and transforming the dataset to ensure data quality and consistency.

3. **Data Storage**  
   - Load the cleaned data into **SQL Server** for efficient querying and analysis.

4. **Data Analysis**  
   - Write SQL queries to answer interesting and business-critical questions based on the dataset.

---

## Dataset  
The dataset contains information about sales transactions and includes the following fields:

- `product_id`: Unique identifier for each product.  
- `sale_price`: The price at which a product was sold.  
- `category` and `sub_category`: Hierarchical categorization of the products.  
- `region`: Geographic region where the order was placed.  
- `order_date`: The date the order was made.

---

## Questions Answered  
The analysis answers some insightful questions, such as:
- What are the total sales per region?  
- Which category and sub-category have the highest revenue?  
- What are the top-selling products?  
- How do sales trends vary over time?

---

## Technologies Used  
- **Python**: For data processing and integration.  
  - Libraries: `pandas`, `numpy`, `sqlalchemy`, `os`  
- **SQL Server**: For data storage and analysis.  
- **Kaggle API**: For dataset acquisition.

---

## How to Run  

### Prerequisites:
- Install Python (3.x recommended).  
- Set up SQL Server and configure a database.  
- Install the required Python libraries using the following command:
  ```bash
  pip install pandas numpy sqlalchemy kaggle
