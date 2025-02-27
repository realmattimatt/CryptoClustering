# CryptoClustering

## **Table of Contents**

- [CryptoClustering](#cryptoclustering)
  - [**Table of Contents**](#table-of-contents)
  - [**Project Overview**](#project-overview)
  - [**Technologies / Dependencies Needed and Used**](#technologies--dependencies-needed-and-used)
  - [**How to Run the Application**](#how-to-run-the-application)
  - [**Visualizations**](#visualizations)
  - [**Data Source**](#data-source)
  - [**Sources**](#sources)
  - [**License**](#license)
  - [**Project By**](#project-by)
  - [**Contact**](#contact)

## **Project Overview**
Using the [Crypto_Market_data](Resources/crypto_market_data.csv)
I used 2 different forms of normalizing data, as well as grouping the data by K_means of PCA. 

## **Technologies / Dependencies Needed and Used**
- **Pandas**: Used for handling and analyzing large datasets, particularly in tabular form (e.g., DataFrames).
- **hvplot.pandas**: Used for interactive plotting in Python, specifically designed to work seamlessly with Pandas DataFrames. It allows you to create interactive plots directly from your data, enhancing visualization capabilities.
- **sklearn.cluster.KMeans**: Part of scikit-learn (sklearn), a popular machine learning library in Python. KMeans is an algorithm used for clustering data into groups (clusters) based on similarity. It's useful for unsupervised learning tasks where you want to identify patterns or groupings in data.
- **sklearn.decomposition.PCA**: Also from scikit-learn, PCA stands for Principal Component Analysis. A technique used for dimensionality reduction in data, particularly useful when dealing with datasets with many variables. PCA transforms the data into a new set of variables (principal components) that are linear combinations of the original variables, retaining as much variance as possible.
- **sklearn.preprocessing.StandardScaler**: 
Another component of scikit-learn, StandardScaler is used for standardizing features by removing the mean and scaling to unit variance. This preprocessing step is common in machine learning pipelines to ensure that all features contribute equally to the model and to improve the performance of certain algorithms that are sensitive to the scale of the input data.


## **How to Run the Application**
- 1. Install Technologies / Dependencies Needed and Used. See - [**Sources**](#sources) for additional information.
- 2. Open and run the jupyter notebook top to bottom.
## **Visualizations**
[Data Processing Sample pt.1](Images/df_market_data_head_sample.png)

[Data Processing Sample pt.2](Images/df_market_data_line_chart.png)

[Data Processing Sample pt.3](Images/df_market_data_summary_stats.png)

[Data Processing Sample pt.4](Images/df_market_scaled_head_sample.png)

[Data Processing Sample pt.5](Images/df_market_scaled_scatterplot.png)

[Data Processing Sample pt.6](Images/elbow_curve.png)

[Data Processing Sample pt.7](Images/pca_total_explained_variance.png)

[Data Processing Sample pt.8](Images/elbow_curve2.png)

[Data Processing Sample pt.9](Images/K_means_PCA.png)

[Data Processing Sample pt.10](Images/Dual_elbow_curves.png)


## **Data Source**
[StatLib 1993 Graphics Exposition](http://lib.stat.cmu.edu/datasets/1993.expo/)

## **Sources**
* Office hours / instructional time / T.A.'s
* [hvplot.pandas](https://hvplot.holoviz.org/user_guide/Pandas_API.html)
* [sklearn.Kmeans.cluster](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
* [sklearn.decomposition](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html)
* [sklearn.preprocessing.StandardScaler](sklearn.preprocessing.StandardScaler)
* Xpert Learning Assist
* Google
* ChatGPT

## **License**
This project is licensed under the [GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007](./LICENSE) - see the LICENSE file for details here.

## **Project By**
**Matthew Matti**

## **Contact**
For any questions or feedback, feel free to reach out to me at [mattimatt@hotmail.com](mailto:mattimatt@hotmail.com).

![License](https://img.shields.io/badge/license-GPL%203-blue)
