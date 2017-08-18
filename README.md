# cBioPortal-Advanced-Data-Analysis

This repository is my application for the cBioPortal Google Summer of Code Internship position.

The main file is **cBioPortal_Data_Analysis.ipynb** Jupyter notebook in which I demonstrated how different studies (RDBMS equivalent of a table) 
could be clustered together into types of studies based on the attributes measured (column names and contents of columns).  

The goal of the project was to develop a clustering algorithm that would recognize and cluster all of the studies into different study types.  

In the Jupyter notebook I did the following:  
First I parsed data from a REST API providing data in JSON format into pandas dataframes.  
Then I showed graphically the results of clustering of studies based on measured attributes.  
Lastly, I implemented similarity scoring functions to score the similarity of studies based on values of attributes (columns in a table) and graphically plotted those results in a heatmap using Seaborn package.

