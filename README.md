<h1>Customer Segmentation using K-Means Clustering</h1>
<p>This project aims to understand the customers of a supermarket mall by analyzing their basic data such as customer ID, age, gender, annual income, and spending score. The objective is to find meaningful clusters of customers with respect to their spending scores so that the marketing team can plan their strategy accordingly.</p>
<h2>Dataset</h2>
<p>The dataset used in this project is obtained from <a href="https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python">Kaggle</a>. It has 200 samples and 5 features:</p>
<ul>
<li>CustomerID: Unique ID assigned to each customer</li>
<li>Gender: Gender of the customer</li>
<li>Age: Age of the customer</li>
<li>Annual Income (k$): Annual Income of the customer</li>
<li>Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature</li>
</ul>
<h2>Methodology</h2>
<p>To cluster the customers based on their spending scores, we use an unsupervised machine learning algorithm called k-means clustering. K-means clustering partitions a set of observations into k clusters where each observation belongs to the cluster with the nearest mean.</p>
<p>In this project, we first explore the dataset by visualizing the distribution of each feature and checking for missing values. Then, we scale the features and determine the optimal number of clusters using the elbow method. Finally, we apply k-means clustering to the scaled data and visualize the clusters.</p>
<h2>Results</h2>
<p>After performing k-means clustering on the dataset, we obtain distinct clusters of customers based on their spending scores. This segmentation provides valuable insights into the customers and can be used by the marketing team to plan their strategy accordingly.</p>
