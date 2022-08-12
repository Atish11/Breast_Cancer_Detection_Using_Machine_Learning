# Breast_Cancer_Detection_Using_Machine_Learning

Breast_Cancer_Detection_Using_Machine_Learning

The goal is to see which features are most useful in forecasting whether a cancer is malignant or benign and to look for general trends that may help us with the model’s section and hyper-parameter choice. The goal is to determine if the cancer is malignant or benign. To do this, I fitted a program that can predict the categorical class of fresh input using machine learning classification algorithms.


## Screenshots

I have used a dataset that is available on Kaggle. I am going to use Jupyter to work on this dataset. At first, I will import all the necessary libraries which will make it easier to write the program. Then I will load the dataset and I will show a sample of the first 10 rows of the data from the dataset. Here each row of the data represents a patient that may or may not have cancer. Then I will explore the data and count the number of rows and columns in the dataset. There is a total of 593 rows and 32 columns in the dataset which means there are 32 features or data points for each patient.

The next step is to Count the number of columns that have no values in them. I have noticed that all the columns contain some null or empty values. Now, that the cleaning process starts I will remove the empty values because it adds no values to the original data collection

After cleaning the data I can get a new count of how many rows and columns there are. which are 569 rows and 32 columns. Now I will be counting the patients with malignant cells (M) and non-cancerous cells (B). I found that there are 212 Cancerous Cells and 357 Non-Cancerous cells. I will visualize this count on a chart displaying Malignant and Benign diagnoses.

### Visualize the count of cancerous and non-cancerous diagnosis
<img src="https://user-images.githubusercontent.com/78890102/184340675-eaa57bd7-35ff-4909-81c6-da76b3a1173d.png">

The next step is to Change the M and B numbers in the diagnostic column to 0 or 1 accordingly. as when I looked at the data type I see Except for the last column/feature, all columns/features are integers. diagnosis column. Now I will be creating a pair plot which is also called as a scatter plot, in which the value of one factor in the same record row is match with the value of another variable in same data row. I will be showing a pair plot of 6 columns highlighting the diagnosis that are 0 and 1.

### Pair plot of 6 of the columns highlighting the diagnosis (points in 0 and 1)
<img src="https://user-images.githubusercontent.com/78890102/184340685-fa591885-3ce3-4994-9013-c1f579dc3013.png">

The next step is to get the correlation of the columns and visualize the correlation by creating a heat map.

### Visualizaion of the correlation of 10 columns by creating heat map
<img src="https://user-images.githubusercontent.com/78890102/184340697-7df19ddb-e66f-4893-90cf-89f77f3bf1fe.png">


