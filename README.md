# Crypto Clustering Analysis

<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name=" Rental-Market-Data-San-Fran"></a>
<img src="https://github.com/Nievz/Crypto_Clustering/blob/main/Images/coins.png">

<!-- ABOUT THE PROJECT -->
## About The Project

  <p align="center"> 
    The purpose of this analysis is to groups cryptocurrencies according to their performance over various time periods. We then graph the results so that the performance can be represented visually. Using the original data, we determine the optimal value for k using the elbow method. Using the K-means algorithm and the optimal value for k, we cluster the cryptocurrencies based on the supplied price changes of the cryptocurrencies. Then, using PCA, the features are reduced to three principal components. Lastly, we conduct a visual analysis of the cluster analysis results by comparing the outcome with and without optimization techniques. 
  </p>

  <p align="center" style="display: flex;" >
<img src="https://github.com/Nievz/Crypto_Clustering/blob/main/Images/cryptocurrency.png" alt="Logo" width="50" height="50">  
<img src="https://img.shields.io/npm/l/express" />
<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/tyleradammartinez/SIG-Dashboard-Application" />
    <img src="https://github.com/Nievz/Crypto_Clustering/blob/main/Images/cryptocurrency.png" alt="Logo" width="50" height="50"> 
</p>


## The high-level steps for this Analysis are as follows:
`We import the raw data` <br>
`We prepare the data for analysis`<br>
`We find the best value for k by using the original data` <br>
`We cluster the cryptocurrencies with K-means by using the original data` <br>
`We optimize the clusters with principal component analysis` <br>
`We find the best value for k by using the PCA data` <br>
`We then cluster the cryptocurrencies with K-means by using the PCA data` <br>
`And we finalze by Visualizing and comparing the results` <br>
    
## Required Python Libaraies

### CALCULATIONS
`import pandas as pd` <br>
`shimport hvplot.pandas`<br>
`from pathlib import Path` <br>
`from sklearn.cluster import KMeans` <br>
`from sklearn.decomposition import PCA` <br>
`from sklearn.preprocessing import StandardScaler` <br>
`import warnings` <br>
`warnings.filterwarnings('ignore')` <br>

<!-- GETTING STARTED -->
## Data and Research Design

### Variable Plot

  <p align="center">
  </p>

<img src="https://github.com/Nievz/Crypto_Clustering/blob/main/Images/Variable%20plot.png"> 

### Elbow Curve

  <p align="center">
  </p>

<img src="https://github.com/Nievz/Crypto_Clustering/blob/main/Images/Elbow%20Curve.png"> 

### Predicted Clusters

  <p align="center">
  </p>

<img src="https://github.com/Nievz/Crypto_Clustering/blob/main/Images/predicted%20cluster.png"> 

### Predicted Elbows

  <p align="center">
  </p>

<img src="https://github.com/Nievz/Crypto_Clustering/blob/main/Images/predicted%20elbow.png"> 

## Conclusion

  <p align="center">
    
  ## Question: What is the best value for k when using the PCA data?
        Answer: 4

  ## Question: Does it differ from the best k value found using the original data?
        Answer: No, they are both the same value at 4
 
 ## Question: After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

        Answer: Lower number of clusters will provide a higher level of optimization within the data. The higher the number of clusters the lower the inertia index.

  </p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [https://bootcampspot.instructure.com/courses/3828/assignments/57438?module_item_id=1009909]()
* [https://scikit-learn.org/stable/modules/clustering.html#clustering]()
* [https://holoviz.org/tutorial/Interlinked_Plots.html]()
* [https://holoviz.org/tutorial/Interactive_Pipelines.html]()
* [https://hvplot.holoviz.org/user_guide/Pandas_API.html]()
* [https://www.youtube.com/watch?v=ikt0sny_ImY]()
* [https://github.com/othneildrew/Best-README-Template/blob/master/BLANK_README.md]()
  
  
