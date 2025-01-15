# Analysis-of-Chemical-Components-Project

## Project Overview
This repository contains the data and analysis scripts for the "Analysis of Chemical Components" project. The project aims to analyze and process information about cosmetic products, focusing on their ingredients and properties using Python.  

## Project Structure
   * __data.csv__: The dataset containing various chemical components and their properties.  

   * __analysis.py__: The Python script used for data analysis, transformation, and visualization.  

   * __README.md__: This file, providing an overview of the project.

## Key Features  
### Data Processing  
  * __Import Libraries__: Utilizes essential libraries such as numpy and pandas for data manipulation. 
  * __Matrix Dimensions__: Computes the dimensions for a matrix based on the dataset.  
  * __Matrix Population__: Populates the matrix with values based on ingredient occurrences in products.  
### Data Transformation  
  * __TSNE Transformation__: Applies t-distributed Stochastic Neighbor Embedding (TSNE) for dimensionality reduction and feature extraction.  
### Data Visualization  
  * __Scatter Plot__: Creates an interactive scatter plot using Plotly Express to visualize TSNE features.  
  * __Interactive Tooltips__: Enhances the plot with hover tooltips displaying additional information.  

### Structure
The dataset consists of the following columns:
1. __Label__: The type/category of the cosmetic product (e.g., Moisturizer, Eye cream, Treatment, Cleanser).
2. __Brand__: The brand name of the cosmetic product (e.g., BOBBI BROWN, WANDER BEAUTY, DIOR, OLEHENRIKSEN, CLINIQUE).
3. __Name__: The specific name of the cosmetic product (e.g., BB Cream SPF 35, Baggage Claim Rose Gold Eye Masks).
4. __Price__: The price of the cosmetic product in the respective currency.
5. __Rank__: The rank or rating of the cosmetic product (e.g., 3.9, 4.6, 4.9).
6. __Ingredients__: The list of ingredients used in the cosmetic product. Note that some entries might be truncated with "..." indicating incomplete ingredient lists.
7. __Combination__: Binary indicator (1/0) denoting if the product is suitable for combination skin type.
8. __Dry__: Binary indicator (1/0) denoting if the product is suitable for dry skin type.
9. __Normal__: Binary indicator (1/0) denoting if the product is suitable for normal skin type.
10. __Oily__: Binary indicator (1/0) denoting if the product is suitable for oily skin type.
11. __Sensitive__: Binary indicator (1/0) denoting if the product is suitable for sensitive skin type.

### Data Cleaning and Preparation
   * __Missing Values__: Handle any missing values by filling them with appropriate measures (e.g., mean, median, mode) or by removing incomplete rows if necessary.
   * __Normalization__: Normalize the data for accurate comparison and analysis.
   * __Categorical Encoding__: Convert categorical variables into numerical values using techniques like one-hot encoding.
### Analysis Focus
  * __Correlation Analysis__: Explore the relationships between different properties of cosmetic products (e.g., price vs. rank).
  * __Cluster Analysis__: Group similar products based on their properties using clustering techniques.
  * __Trend Analysis__: Identify trends and patterns in the data, such as the prevalence of certain ingredients across different brands.
### Visualization
  * __Scatter Plots__: Visualize the relationships between different properties (e.g., price vs. rank).
  * __Bar Charts__: Show the distribution of products in various categories (e.g., number of moisturizers, eye creams).
  * __Heatmaps__: Display the correlation between different properties.
### Tools and Libraries
  * __Pandas__: For data manipulation and analysis.
  * __Numpy__: For numerical operations.
  * __Matplotlib and Seaborn__: For data visualization.
  * __Scikit-learn__: For machine learning and clustering.
  * __Plotly__: For interactive visualizations.

### Dependencies
  * __Python 3.x__
  * __numpy__
  * __pandas__
  * __scikit-learn__
  * __plotly__

 ### Contributing
  Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue 
  first to discuss what you would like to change.

### License
This project is licensed under the MIT License.

### Contact
For any questions or inquiries, please contact Your Name. 
