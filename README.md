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
In order to use the BigQuery API we need to import the right library for our resource, in this case BigQuery

```
from google.cloud import bigquery
```
## Move forward
From this point ahead you will specify to which [Dataset](https://cloud.google.com/bigquery/docs/datasets-introand) table you will access. We will use Public Datasets that are available in BigQuery for us to practice.

## Public Datasets used in these Examples

- [Chicago News](https://github.com/mtpradoc/BigQueryAPI/blob/main/01_Access_Dataset_Chicago_Crime.ipynb)
- [Chicago Crime](https://github.com/mtpradoc/BigQueryAPI/blob/main/01_Access_Dataset_Chicago_Crime.ipynb)
- [Open Air Quality](https://github.com/mtpradoc/BigQueryAPI/blob/main/02_Access_Dataset_Open_Air_Quality.ipynb)
- [Hacker News](https://github.com/mtpradoc/BigQueryAPI/blob/main/03_Group_By%2C_Having_Dataset_Hacker_News.ipynb)
- [World Bank International Education](https://github.com/mtpradoc/BigQueryAPI/blob/main/04_Order_By_Dataset_World_Bank_International_Education.ipynb)
- [Chicago Taxi Trips](https://github.com/mtpradoc/BigQueryAPI/blob/main/05_AS_%26_WITH_Dataset_Chicago_Taxi_Trips.ipynb)
- [Stack Overflow](https://github.com/mtpradoc/BigQueryAPI/blob/main/06_JOINING_DATA_Dataset_Stack_Overflow.ipynb)
