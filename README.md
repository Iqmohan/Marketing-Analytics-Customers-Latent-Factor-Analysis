Marketing-Analytics-Customers-Latent-Factor-Analysis
Implemented marketing analytics leveraging Latent Factor Analysis (LFA) to uncover hidden patterns and relationships within customer data. Employing agglomeration techniques and dendogram visualization, we clustered customers based on similar behaviors and attributes. This approach enabled us to segment the customer base effectively, identifying distinct groups with shared characteristics. By understanding these latent factors, we gained insights into customer preferences, enabling targeted marketing strategies and personalized customer experiences.
Steps Involved :
step 1 - Load the dataset


step 2 getting the shape of the dataset

step 3 - getting the information about the dataset

step 4 - getting the statistical data of the dataset

step 5 - getting the datatype in the dataset

step 6 - finding the missing data

step 7 - plotting the distribution to visualize the outliers

step 8 - now we will see if there are outliers in the data

step 9 - identifying the outliers

step 10 - removing the outliers

step 11 - Feature engineering

step 12 - finding the unique values in the dataset where we have the category of input plotting the distribution of boxplot.

step 13- changing the education status

step 14 - step 1 creating 'is_parent' to indicate the parenthood

step 15- Creating total spending in the last 2 years

step 16 -Average monthly visits to the company's website

step 17 - Ratio of the online purchases to the total purchases

EDA
step 18 This graph will show the distribution of income column which represents each customer. The x-axis shows the range of incomes, and the y-axis shows the number of customers who fall into each range.

Total Campaigns Accepted Distribution

step 19 In this we are plotting a histogram of Total_Campaigns_Accepted. This plot show us the distribution of the number of campaign accepted by each customer.

now we are going to see the difference between NumWebPurchases vs NumStorePurchases

step 20 scatter plot of NumWebPurchases vs NumWebVisitsMonts for chekcing the correlation between purchases and visits

step 21 performing datascaling using the StandardScaler initializing the minmax scaler

step 22 Customer Clustering with PCA, KMeans and Agglomerative for a Marketing Campaign

Determining the optimal number of clusters using Silhouette Score step 23: finding best k value

The silhouette score ranges from -1 to 1:

A score close to +1 indicates that the sample is far away from the neighboring clusters.

A score of 0 indicates that the sample is on or very close to the decision boundary between two neighboring clusters.

A score close to -1 indicates that those samples might have been assigned to the wrong cluster.

In summary, the silhouette_score measures how dense and well-separated the clusters are in your data, helping you to evaluate the effectiveness of your clustering algorithm and the number of clusters chosen. A higher silhouette score suggests better-defined clusters.

conclusion: The code starts by loading a tab-separated file into a Pandas dataframe. It then performs various operations to understand the structure and content of the data, including getting the number of rows and columns, checking for missing data, and getting summary statistics. The code then performs data preprocessing, including one-hot encoding of categorical variables and scaling of numerical variables. The data is then reduced to 8 components using PCA, and two clustering algorithms (KMeans and Agglomerative Clustering) are applied to the data.

Finally, various evaluation metrics are used to assess the quality of the clustering results. The code visualizes the results of the clustering, as well as the relationships between different variables in the data, through various types of plots, including histograms, box plots, scatter plots, violin plots, and pair plots.


Plots and Clustering Depiction :
![image](https://github.com/Iqmohan/Marketing-Analytics-Customer-s-Latent-Factor-Analysis/assets/159016465/6e3a61df-17d1-4a9f-bcf2-92c7919ead56)
![image](https://github.com/Iqmohan/Marketing-Analytics-Customer-s-Latent-Factor-Analysis/assets/159016465/6f838ba7-a084-4cfa-a27c-10d4c06fc745)
![image](https://github.com/Iqmohan/Marketing-Analytics-Customer-s-Latent-Factor-Analysis/assets/159016465/e47d331e-eb25-439b-bfe9-3fa932687660)
![image](https://github.com/Iqmohan/Marketing-Analytics-Customer-s-Latent-Factor-Analysis/assets/159016465/f0a4b0b3-21fb-4fce-89f0-dc900866aabe)
![image](https://github.com/Iqmohan/Marketing-Analytics-Customer-s-Latent-Factor-Analysis/assets/159016465/8b76a5f9-5f9f-4822-b397-43022fe74396)






