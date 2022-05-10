# 10-challenge
 Jupyter notebook that clusters cryptocurrencies by their performance in different time periods & visulizes these clusters


## Technologies
* import pandas as pd
* import hvplot.pandas
* from path import Path
* from sklearn.cluster import KMeans
* from sklearn.decomposition import PCA
* from sklearn.preprocessing import StandardScaler


## Installation Guide
Using the Conda package manager: [GitHub](https://github.com/ALovettII/10-challenge.git)

You will also the following libraries:
```
# Activate your Conda dev environment
conda activate dev

# Install scikit-learn
pip install -U scikit-learn

# Install hvPlot
conda install -c pyviz hvplot
```

## Usage
Running this program will allow the following:
* Import the Data (provided in the starter code)
* Prepare the Data (provided in the starter code)
* Find the Best Value for `k` Using the Original Data
* Cluster Cryptocurrencies with K-means Using the Original Data
* Optimize Clusters with Principal Component Analysis
* Find the Best Value for `k` Using the PCA Data
* Cluster the Cryptocurrencies with K-means Using the PCA Data
* Visualize and Compare the Results



## Contributors
Created by Arthur Lovett