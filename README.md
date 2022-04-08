# Crypto_Analysis


# Overview of Analysis

The purpose of this analysis is take Crypto Data and use Unsupervised ML (using KMeans) to group the data into seperate classes. 

To begin, the data was loaded in and a lot of cleaning took place, such as: removing null values, setting index values to crypto names, converting categorical values into numeric for the ML algorithm, and scaling / normalizing the data. 

From here, PCA (Principle Component Analysis) was used to reduce the number of dimensions of the data set to 3.
Next, an elbow curve was generated in order to determine the appropriate number of K clusters to use in our KMeans algorithm. 
The algorithm was then created and was used to predict the classes. Furhter scaling was then used in order to create a few visualizations which highlight the distinct predicted classes of the crypto data.
