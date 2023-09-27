# k-Means Clustering on Wine data using Numpy Python

Our dataset consists of wine data, which consists of the following set of features:
- Alcohol content
- Malic Acid
- Ash
- Alkalinity
- Magnesium
- Hue
And others. We utilize a k-means algorithm to perform clustering of these wines on the basis of these features.

### Step 1: Data Cleaning

We check for missing values and remove them if any are present. We also check for incorrect values.

### Step 2: Exploratory Data Analysis

We carry out some data visualization to understand the distribution of the features better. We create scatter plots, distribution plots, and histograms in our analysis. Here are some of those visualizations:

![image](https://github.com/zahra-q/k-means-clustering-using-numpy/assets/58932323/9a751f5e-17d0-4a9b-a356-10dea835c208)

![image](https://github.com/zahra-q/k-means-clustering-using-numpy/assets/58932323/f81b37fc-2495-4015-a296-b491cbbecc51)

![image](https://github.com/zahra-q/k-means-clustering-using-numpy/assets/58932323/b65c65e1-0c3c-4588-958d-06559b2b8518)


### Step 3: Building a Model 

We see that k=3 gives us the best results. The data was clustered on the basis of the Malic acid and Hue features. We ran 1000 iterations of the algorithm since insufficient iterations would lead to poor results. With large number of iterations, we ensure that our algorithm converfes where our centroids do not change. 
