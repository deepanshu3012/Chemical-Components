Cosmetic Product Analysis with t-SNE
Project Overview
This project focuses on analyzing cosmetic product data using t-Distributed Stochastic Neighbor Embedding (t-SNE), a dimensionality reduction technique. The goal is to visualize high-dimensional data in a two-dimensional space, enabling us to identify patterns and clusters among cosmetic items based on their composition and features.

The analysis emphasizes:

Understanding relationships between product categories.
Identifying similarities between items without requiring a chemistry background.
Filtering data based on specific categories and skin types for targeted insights.
Features
Data Filtering:
Focused analysis on specific categories (e.g., moisturizers) and skin types (e.g., dry skin).
Dimensionality Reduction:
Used t-SNE to project high-dimensional data (2233 features) into 2D space for visualization.
Interactive Visualization:
Created a scatter plot with hover tools using Bokeh to display detailed information for each product (e.g., name, brand, price, and rank).
Similarity Mapping:
Highlighted relationships between products based on their proximity in the t-SNE plot.
Project Workflow
Data Preparation:

Filtered the dataset for specific product categories and skin types.
Reset indices to create a focused subset for analysis.
Dimensionality Reduction with t-SNE:

Reduced 2233 features into two dimensions.
Parameters optimized to ensure effective clustering.
Visualization with Bokeh:

Plotted the t-SNE results on a scatter plot.
Integrated hover tools to provide product-specific details interactively.
Interpretation:

Explained how to interpret the t-SNE plot, emphasizing proximity as an indicator of similarity.
Technologies Used
Python:
Libraries: pandas, scikit-learn, bokeh, and numpy.
Bokeh:
For interactive data visualization with hover tools.
t-SNE (from scikit-learn):
For dimensionality reduction and creating clusters.
