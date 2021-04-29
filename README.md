# How to use Big Query API

Refer to [Biquery API](https://cloud.google.com/bigquery/docs/reference/rest) documentation.

## 1. Authenticate
In order to use the Google Cloud Platfomr in Colab we need to authenticate our GCP account. 

```
from google.colab import auth
auth.authenticate_user()
```

## 2. Specify Project
This step include specify the project on which we are going to work in our GCP Platform.

```
project_id = "YOUR_PROJECT_ID"
```

## 3. Import BigQuery API library
In order to use the BigQuery API we need to import the right library for our resource, in this case BigQuery

```
from google.cloud import bigquery
```


