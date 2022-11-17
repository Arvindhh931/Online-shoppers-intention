# Online shoppers intention to know weather Web Traffic is getting converted into Revenue generation or not

## problem statement

Based on given data of visitors browsing for online shopping, build different clusters to know whether person is only browsing and visiting multiples pages or also generating revenue for the shoppers as well.  Analysis and comparing the clusters formed with the existing Revenue Column.

## Data Set Information:

The dataset consists of feature vectors belonging to 12,330 sessions.The dataset was formed so that each sessionwould belong to a different user in a 1-year period to avoidany tendency to a specific campaign, special day, userprofile, or period.

## Attribute Information:

  The dataset consists of 10 numerical and 8 categorical attributes.'Revenue' attribute can be used as the class label.

  "Administrative", "Administrative Duration", "Informational", "Informational Duration", "Product Related" and "Product Related Duration" represent the number of different types of pages visited by the visitor in that session and total time spent in each of these page categories. 
  The values of these features are derived from the URL information of the pages visited by the user and updated in real time when a user takes an action, e.g. moving from one page to another. 
- The "Bounce Rate", "Exit Rate" and "Page Value" features represent the metrics measured by "Google Analytics" for each page in the e-commerce site. 

- The value of "Bounce Rate" feature for a web page refers to the percentage of visitors who enter the site from that page and then leave ("bounce") without triggering any other requests to the analytics server during that session. 

- The value of "Exit Rate" feature for a specific web page is calculated as for all pageviews to the page, the percentage that were the last in the session. The "Page Value" feature represents the average value for a web page that a user visited before completing an e-commerce transaction. 

- The "Special Day" feature indicates the closeness of the site visiting time to a specific special day (e.g. Mother’s Day, Valentine's Day) in which the sessions are more likely to be finalized with transaction. The value of this attribute is determined by considering the dynamics of e-commerce such as the duration between the order date and delivery date. 


## Exploratory Data Analysis

| *------*  |
|:-------------------------:|
![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/1.png)

| *------*  |
|:-------------------------:|
![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/2.png)

| *------*           |  *----*
:-------------------------:|:-------------------------:
![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/3.png)  |  ![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/4.png) 


| *-----*           |  *-----*
:-------------------------:|:-------------------------:
![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/kmeans.png)  |  ![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/Agglomerative.png)


| *------*  |
|:-------------------------:|
![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/Dendogram.png)

| *------*  |
|:-------------------------:|
![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/10.png)

| *------*  |
|:-------------------------:|
![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/11.png)

| *------*  |
|:-------------------------:|
![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/13.png)

| *------*  |
|:-------------------------:|
![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/12.png)

| *------*  |
|:-------------------------:|
![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/14.png)

| *------*  |
|:-------------------------:|
![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/15.png)

| *------*  |
|:-------------------------:|
![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/16.png)

| *------*  |
|:-------------------------:|
![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/17.png)

| *------*  |
|:-------------------------:|
![](https://github.com/Arvindhh931/Online-shoppers-intention/blob/main/Visualizations/18.png)


## Missing value Imputation


