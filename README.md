This activity uses Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

**1. Prepare the Data**
- Used StandardScaler() module from scikit-learn to normalize the data
- Created a DataFrame with scaled data 

**2. Find the Best Value for k**
- Elbow method was used to find the best value for k

**3. Cluster Cryptocurrencies with K-means**
- Cryptocurrencies were clustered based on determined best value for k
    - fit the K-means model 
    - predicted clusters to group the cryptocurrencies
    - scatter plot was created using hvPlot

**4. Optimize Clusters with Principal Component Analysis**
- Performed a PCA to reduce the features to three principal components
- Retrieved the variance 

**5. Find the Best Value for k Using the PCA Data**
- Elbow method used on the PCA data to find the best value for k

**6. Cluster Cryptocurrencies with K-means Using the PCA Data**
- Cryptocurrencies were clustered based on the best value for k from the PCA data
    - fit the K-means model 
    - predicted clusters to group the cryptocurrencies
    - scatter plot was created using hvPlot








