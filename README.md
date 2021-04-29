# How to use Big Query API
>Marlene Prado

Refer to [Biquery API](https://cloud.google.com/bigquery/docs/reference/rest) documentation.

## 1. Authenticate
In order to use the Google Cloud Platfomr in Colab we need to authenticate our GCP account. 

```
from google.colab import auth
auth.authenticate_user()
```

## 2. Specify your Project
This step include specify the project on which we are going to work in our GCP Platform. In order to perform this step we need to have a gmail account registered in Google Cloud Platform. We can use the GCP free trial for this purpose.

```
project_id = "YOUR_PROJECT_ID"
```

## 3. Import BigQuery API library
In order to use the BigQuery API we need to import the right library for our resource, in this case [BigQuery](https://cloud.google.com/bigquery/docs/introduction)

```
from google.cloud import bigquery
```
## Move forward
From this point ahead you will specify to which [Dataset](https://cloud.google.com/bigquery/docs/datasets-introand) and which table you will access. We will use [Public Datasets](https://cloud.google.com/bigquery/public-data) that are available in [BigQuery](https://cloud.google.com/bigquery/docs/introduction) for us to practice.

## Public Datasets used in these Examples

- [Chicago News](https://github.com/mtpradoc/BigQueryAPI/blob/main/01_Access_Dataset_Chicago_Crime.ipynb). Access using BigQuery API
- [Chicago Crime](https://github.com/mtpradoc/BigQueryAPI/blob/main/01_Access_Dataset_Chicago_Crime.ipynb). Access using BigQuery API
- [Open Air Quality](https://github.com/mtpradoc/BigQueryAPI/blob/main/02_Access_Dataset_Open_Air_Quality.ipynb). Access using BigQuery API
- [Hacker News](https://github.com/mtpradoc/BigQueryAPI/blob/main/03_Group_By%2C_Having_Dataset_Hacker_News.ipynb). Use GROUP BY
- [World Bank International Education](https://github.com/mtpradoc/BigQueryAPI/blob/main/04_Order_By_Dataset_World_Bank_International_Education.ipynb). Use ORDER BY
- [Chicago Taxi Trips](https://github.com/mtpradoc/BigQueryAPI/blob/main/05_AS_%26_WITH_Dataset_Chicago_Taxi_Trips.ipynb). Use AS & WITH
- [Stack Overflow](https://github.com/mtpradoc/BigQueryAPI/blob/main/06_JOINING_DATA_Dataset_Stack_Overflow.ipynb). Use INNER JOIN

Enjoy swimming through this code 🙋‍♀️
