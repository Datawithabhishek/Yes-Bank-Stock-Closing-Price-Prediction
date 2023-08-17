<h1 align='center'> :microscope: Regression Analysis On Yes Bank Stock Closing Price Prediction.<h1>

![--------------------------------------------------------------------------------------------](https://github.com/andreasbm/readme/blob/master/assets/lines/grass.png)






![N|Solid](https://upload.wikimedia.org/wikipedia/commons/d/d1/Yes_Bank_Logo-01.png)




## This repository contains the code and dataset for predicting the closing price of Yes Bank stock using regression analysis. The project uses a dataset containing historical stock prices of Yes Bank from 2005 to 2020

![--------------------------------------------------------------------------------------------](https://github.com/andreasbm/readme/blob/master/assets/lines/grass.png)



## Problem Statement
Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has
been in the news because of the fraud case involving Rana Kapoor. Owing to this
fact, it was interesting to see how that impacted the stock prices of the company
and whether any predictive models can do justice to such situations. This dataset
has monthly stock prices of the bank since its inception and includes closing,
starting, highest, and lowest stock prices of every month. The main objective is
to predict the stock’s closing price of the month.

##  💾 Project Files Description

<p>This Project includes :-
  <li>Google Colab NoteBook</li>
  <li>Project Summary (with the GitHub Repo link inside)</li>
  <li>Presentation Video</li>
</p>




### Data Source:
- [Dataset](https://drive.google.com/file/d/1z4you2Cw3f9eqsXjcnIdIidgOBGgrsbQ/view?usp=sharing) - Dataset taken from AlmaBetter

### Input Files:
  <li><b>data_YesBank_StockPrices.csv</b> - It contains monthly observation of stock parameter such as open, high , low and close.</li>



  ## 🗺️ Roadmap and Navigation guide

<hr>

### Step 1: Data Collection
Collect the historical stock prices of Yes Bank from January 2005 to September 2020. Include variables such as opening price, highest price, lowest price, and closing price and date

<hr>

### Step 2: Data Cleaning and Preprocessing
Clean the dataset by removing any missing values, outliers, or errors. Preprocess the dataset by scaling or normalizing the features as necessary.

<hr>

### Step 3: Regression Model Building
Divide the dataset into training and testing sets. Implement Multiple Linear Regression ,Lasso Regression, Ridge Regression and Elastic net Regression models to predict the closing price of Yes Bank stock. Tune the models by adjusting the hyperparameters to optimize performance.

<hr>

### Step 4: Model Evaluation
Evaluate the models' performance using root mean squared error (RMSE) and mean absolute error (MAE) metrics. Compare the performance of the models to determine which one performs better.

<hr>

### Step 5: Results and Conclusion
Present the results of the regression analysis. Discuss the implications of the results and their potential impact on investors. Provide conclusions and suggestions for future research.

![--------------------------------------------------------------------------------------------](https://github.com/andreasbm/readme/blob/master/assets/lines/grass.png)

## 🛠️ Builds with

![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)

![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)

![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)

![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

![Seaborn](https://img.shields.io/badge/Seaborn-blue?style=for-the-badge&logo=Seaborn)

![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)

![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

![GoogleColab](https://img.shields.io/badge/GoogleColab-orange?style=for-the-badge&logo=GoogleColab)










## :scroll: Conclusion

After implementing various regression model and analyzing their respective performance matrics we came to the conclusion that the <b>"Elastic net Regression"</b> is  top performing models with respect to all the matrics. But when we look for the cross validation score and other factores such as time complexity
