# pca
**Principal component Analysis (PCA)** is one of the most useful algorithm in dimension reduction. PCA is used to investigate multi dimensional data i.e data with huge number of explicative variables. \
The goal of this method is to project the initial raw data on orthogonal factorial plans with less new variables, which maximize the variance of the projected data. In other words, PCA is used to convert a set of observations of possibly correlated variables into a set of values of linearly uncorrelated variables called principal components.\
So, PCA is frequently used to represent the data in low dimension, to investigate the distribution of multi dimensional data, to discover features or clusters in the data.\
PCA can be used for many application. For example:
- **Dimensionality reduction or Data Visualization**:\
For a lot of machine learning applications it helps to be able to visualize your data. Visualizing 2 or 3 dimensional data is not that challenging. However,  when we are faced with 4 or more dimensional data this can be more annoying. You can use PCA to reduce that 4 or more dimensional data into 2 or 3 dimensions so that you can plot and hopefully understand the data better.
- **Speed-up machine learning algorithm**:\
Even if there are more other ways to speed up machine learning algorithm, one solution is PCA. In fact, if your learning algorithm is too slow because the input dimension is too high, using PCA can reduce the hight dimension of data to less dimension data and then to speed it up. This can be a reasonable choice. 
- **Feature extraction**:\
The principal components extract from PCA include most important features from the dataset that are responsible for maximum variance in the output.

_Note: PCA method is used only with quantitative variable. In case of qualitative or categorial variable, recommended algorithm is Multiple Correspondance Analysis (MCA).

# requirements
Python : numpy, scipy, sklearn and other librairies present in the script

r 4.1.3
