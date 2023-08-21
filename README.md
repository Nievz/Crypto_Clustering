# Crypto Clustering

<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name=" Rental-Market-Data-San-Fran"></a>
<img src="https://github.com/Nievz/Project_One_Draft/blob/main/Images/Banner.png">

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="https://github.com/Nievz/Project_One_Draft/blob/main/Images/senate logo.png" alt="Logo" width="200" height="200"> 
  </a>

<h3 align="center"> Crypto Clustering</h3>

</div>




<!-- ABOUT THE PROJECT -->
## About The Project

<img src="https://github.com/Nievz/Project_One_Draft/blob/main/Images/ezgif.com-gif-maker.gif" alt="Logo" width="1000" height="250">
  <p align="center">
    The purpose of this analysis is to groups cryptocurrencies according to their performance over various time periods. We then graph the results so that the performance can be represented visually. Using the original data, we determine the optimal value for k using the elbow method. Using the K-means algorithm and the optimal value for k, we cluster the cryptocurrencies based on the supplied price changes of the cryptocurrencies. Then, using PCA, the features are reduced to three principal components. Lastly, we conduct a visual analysis of the cluster analysis results by comparing the outcome with and without optimization techniques. 
  </p>

  <p align="center" style="display: flex;" >
<img src="https://img.shields.io/npm/l/express" />
<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/tyleradammartinez/SIG-Dashboard-Application" />
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
    Beginning our analysis, we created a visual representation of each senator and state to help draw conclusions on whether or not the geographical location contained any noticeable increases in the number of transactions. In this section, we add geospatial data and use interactive visualizations with GeoViews and hvPlot to investigate the data's relationships. We construct our map using a modified data frame that combines Senators' locations with state coordinates.
  </p>

<img src="https://github.com/MRosan117/senator_trading_performance/blob/main/Images/Map.png"> 

### Elbow Curve

  <p align="center">
    Continuing our analysis, we explore the transactions carried out by senators using an interactive visualization  in the form of a bar chart. We construct our bar chart utilizing Opensource data, which includes the transaction data pertaining to Senators. Based on the data we immediately noticed that 30% of all transactions carried out since 2013 have been done by the state of Georgia. Even more notably, David Purdue (R) is in large part responsible for a vast majority of the data set making up 27% of all transactions during his term in office from 2015 to 2021. Beyond Georgia, the data shows that some large state players are found within Alabama, Delaware, Kansas, and Rhode Island.
  </p>

<img src="https://github.com/MRosan117/senator_trading_performance/blob/main/Images/bokeh_plot(1).png"> 

### Predicted Clusters

  <p align="center">
    Moving on, using an interactive visualization in the form of a bar chart, we investigate the number of transactions carried out by senators in relation to their political party. We construct our bar chart utilizing Opensource data, which includes the transaction data pertaining to Senators. Based on our findings, we see that Republicans are responsible for approximately 4 million transactions whereas Democrats managed a much smaller but still notable 600 thousand.
  </p>

<img src="https://github.com/MRosan117/senator_trading_performance/blob/main/Images/senate_plot.jpg"> 

### Predicted Elbows

  <p align="center">
    For this section of the analysis, we calculate the investments by industry using numerical and visual aggregation and then visualize the results as a bar chart. The goal of this visualization is to identify whether or not senators tend to transact more in industries subject to higher levels of federal regulation. Our findings concluded that not only do senators invest considerably into major banks, a widely recognized heavily regulated industry, but that major pharmaceuticals and semiconductors are not too far behind. In recent years, it is these industries where we have seen a notable increase in policies and legislation that can affect these markets. It is these same industries where senators are more likely to invest and more likely to receive considerable excess returns as we will soon come to find.
  </p>

<img src="https://github.com/MRosan117/senator_trading_performance/blob/main/Images/industry.png" width="900" height="900"> 

### Conclusion

  <p align="center">
    In the end, does being in the Senate equal an advantage in the stock market? The empirical data is not so clear. However, one will be hard-pressed to find a senator who isn't at least performing at the market level. Moreover, we find certain senators doing considerably well for themselves and may warrant further investigation if we had the time. We hope that our findings shed light on the world of Senator trading... and even provide a few traders to follow!
  </p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [https://senatestockwatcher.com/]()
* [https://finance.yahoo.com/]()
* [https://github.com/othneildrew/Best-README-Template/blob/master/BLANK_README.md]()
* [https://holoviz.org/tutorial/Interlinked_Plots.html]()
* [https://holoviz.org/tutorial/Interactive_Pipelines.html]()
* [https://hvplot.holoviz.org/user_guide/Pandas_API.html]()
  
