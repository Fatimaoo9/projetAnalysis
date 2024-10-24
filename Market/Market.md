## Dataset Description

The orders dataset is a well-known dataset used in machine learning and data analysis. It contains information about orders in an online store and includes three main categories of products:

- Grocery Items
- Beverages
- Household Supplies

### Features:
- product_id: Unique identifier for the product.
- product_name: Name of the product.
- order_id: Unique identifier for the order.
- user_id: Unique identifier for the user.
- order_dow: Day of the week the order was placed.
- order_hour_of_day: Hour of the day the order was placed.
- add_to_cart_order: Order in which the product was added to the cart.
- reordered: Indicates if the product was reordered (0 or 1).

### Target:
- Product Purchase Information: Used to analyze customer behavior and predict product orders.

### Statistics:
- Contains multiple files, encompassing hundreds of thousands of rows and multiple columns.
- All values are present, with no missing data.

### Uses:
This dataset is used to develop classification models and analyze customer behavior, making it ideal for machine learning applications and market analysis.

## Libraries Used
- Pandas: A data analysis library used for loading and processing data in the form of DataFrames.

  - Functions: Reading, exploring, and preparing data for analysis.

- Scikit-learn: A machine learning library used for splitting data, training models, and evaluating their performance.

  - Functions: 
    - `train_test_split`: Splitting data into training and testing sets.
    - `GaussianNB`: Implementing the Gaussian Naive Bayes model.
    - `accuracy_score` and `classification_report`: Evaluating model performance.

- Matplotlib: A data visualization library used for creating charts and graphs.

  - Function: Visualizing results to better understand performance.
