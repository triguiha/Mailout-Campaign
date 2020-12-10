# Mailout-Campaign
This project concerns a company that performs mail-order sales in Germany. Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. Provided by General Population Demographic dataset and the company customers dataset, this project performs unsupervised learning techniques to organize the general population into clusters, then use those clusters to see which of them comprise the main user base for the company.

# Usage
- The project starts with importing libraries and loading data
- Assess missing data and drop columns/rows with many missing elements
- Re-encoded attributes with mixed features
- Apply feature transformation by imputing the missing values to the mean of the elements
- Perform Dimension reduction using the Principal Component Analysis PCA
- Select the first 30 PCA components and compare attributes weights to the highest three principle components
- Apply clustring on General depographic population dataset using KMEANS for varying centers
- Select optimal number of centers 
- Apply data cleaning on the company dataset and predict the clustring
- Compare both results
