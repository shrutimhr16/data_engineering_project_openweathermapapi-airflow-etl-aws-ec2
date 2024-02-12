# data_engineering_project_openweathermapapi-airflow-etl-aws-ec2
ETL using Open Weather Map API  on AWS  using Airflow

Extract --> Open Weather Map API 

Transform --> Python   

Load --> S3 bucket in csv format

Orchestration --> Airflow

Workflow :- This project is fetching data from https://openweathermap.org/api. You might have to register first and configure key for fetching realtime API data. It will first check availability of the API, then fetch weather data for city mentioned in API call, perform transformation on data and finally load result of tranformed data into AWS S3 Bucket.

<h3> Steps: </h3>

Step1 --> Launch an EC2 instance on AWS and download airflow and required libraries.

Step2 --> Create a S3 bucket for loading data. Allow access to this bucket to EC2 instance.

Step3 --> Create an account on open weather map and access API keys.

Step4 --> Create dag to extract data from API and perform transformations using Python and load it to S3 bucket in csv format.

Output csv files:-
<img width="961" alt="Screenshot 2024-02-12 at 3 28 45 PM" src="https://github.com/shrutimhr16/data_engineering_project_openweathermapapi-airflow-etl-aws-ec2/assets/42519482/3355e017-f3d1-4d48-88e8-b345a7fee775">

