# crypto_investments

# Executive Summary
An example of using clustering to visualize data.
    - Using Elbow Curves to predict the optimal number of clusters
    - Using PCA method to reduce the number of dimensions to analyze
    - Plotting the data to compare original analysis vs the PCA method

# Import required libraries and dependencies
import pandas as pd
import hvplot.pandas
from path import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler

# Credits
UC Berkeley Fintech Bootcamp