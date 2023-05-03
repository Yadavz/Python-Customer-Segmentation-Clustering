# Customer Segmentation Using Clustering

This project aims to segment customers of a mall based on their annual income and spending score. The dataset used for this project is "Mall_Customers.csv", which contains information on the customer's gender, age, annual income, and spending score. The project uses unsupervised learning techniques like clustering to group similar customers together. The project uses Python's popular data science libraries like Pandas, Seaborn, Matplotlib, and Scikit-Learn.

## Requirements

To run this project, the user needs to have Python 3 installed on their system, as well as the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Exploratory Data Analysis

The first part of the project is univariate analysis, where the distribution of each variable is plotted using various visualization techniques. For instance, histograms, kernel density plots, and box plots are used to visualize the distribution of age, annual income, and spending score separately. The project also investigates the correlation between variables using a heatmap.

## Clustering

The second part of the project is clustering, where customers are grouped into different clusters based on their similarity. In the first clustering, only annual income is considered, and K-means clustering is used to form groups. The optimal number of clusters is determined using the elbow method. In the second clustering, both annual income and spending score are considered, and again, K-means clustering is used. The optimal number of clusters is determined using the inertia score. The resulting clusters are visualized using scatter plots, and the mean values of different variables for each cluster are calculated.

## Gender and Customer Segments

Finally, the project investigates the gender distribution in each cluster using a cross-tabulation table. 

## Benefits

This project is an excellent example of how clustering techniques can be used to segment customers based on their characteristics. By understanding the different customer segments, the mall can tailor its marketing and advertising strategies to attract more customers and retain existing ones. This project can be extended by including more variables and exploring different clustering algorithms.

## Implementation Details

The project uses Python to perform data analysis and clustering. The K-means clustering algorithm is applied to the data using scikit-learn, and the results are visualized using matplotlib and seaborn. Cross-tabulation analysis is performed using pandas, and the mean values of each customer segment are calculated using pandas as well.

Overall, this project provides a detailed and informative example of how clustering can be used to segment customers and help businesses make data-driven decisions.

