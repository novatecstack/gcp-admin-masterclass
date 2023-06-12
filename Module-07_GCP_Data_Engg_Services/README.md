# Google Cloud Data Engineering, and Analytics
In this module, we will learn how to design and build data processing systems. With Google Cloud services, you can seamlessly leverage data and gain real-time insights that improve your decision-making and accelerate innovation. 
Here, we will try to learn how to enable data-driven decision making by collecting, transforming, and publishing data. Before we explore google's data services, lets have a quick overview of different roles that you may play while processing the data:

- A *Data Engineer* should be able to design, build, operationalize, secure, and monitor data processing systems with a particular emphasis on security and compliance; scalability and efficiency; reliability and fidelity; and flexibility and portability.

- A *Data Analysts* gather data, analyze that data and translate the results into insights to share with business stakeholders.

- A *Database Engineer* designs, creates, manages, migrates, and troubleshoots databases used by applications to store and retrieve data.
## 1. Overview
   - Data Engineering is the foundation for the new world of Big Data. As companies become more reliant on data, the importance of Data Engineering continues to grow. Companies are discovering new ways to use data to their advantage. They use data to analyze the current status of their business, forecast the future, model their customers, avoid threats and develop new offerings. </br>
   - Data Engineering is a field that deals with data analysis and activities such as obtaining and storing data from various sources. Then, take the data and clean them up so they may be used in other processes like Data Visualisations, Business Analytics, and Data Science solutions. 
   - Data Engineering ultimately aims at providing ordered and consistent data flow to permit the processing of data.
   ![image](https://github.com/novatecstack/gcp-admin-masterclass/assets/121426292/7936cdee-bbbd-4d3f-86ad-376d237cd189)

## 2. Cloud Storage (for binary data)
## 3. Cloud Block Storage
   - Direct Attached - <b>*Local SSD*</b>
   - Network Attached - <b>*Persistent Disk*</b>
## 4. Data Transfer Services
   - <b>*Storage Transfer Service*</b>
   - <b>*gsutil*</b>
   - <b>*Transfer Appliance*</b> (> 20 TB data OR more than a week to migrate)
## 5. GCP Database Services (SQL)
   - <b>*Cloud SQL*</b>
   - <b>*Cloud Spanner*</b>
## 6. GCP Database Services (NoSQL)
   - <b>*Cloud MemoryStore*</b> 
   - <b>*Cloud FileStore*</b>
   - <b>*Cloud DataStore*</b>
   - <b>*Cloud BigTable*</b>
## 7. GCP Data Processing Services
   - [<b>*Cloud BigQuery*</b>](https://cloud.google.com/bigquery)
     - Google BigQuery is a serverless, fully managed cloud data warehouse service offered by Google. 
     - It allows you to import, and manage petabytes of data. 
     - It offers rapid SQL queries and interactive analysis of massive datasets. 
     - It also has built-in, powerful Machine Learning capabilities.
   - [<b>*Cloud DataFlow*</b>](https://cloud.google.com/dataflow)
     - Dataflow is a cloud-based data processing service that is used for batch and real-time data streaming. 
     - It allows developers to create processing pipelines for integrating, preparing, and analyzing massive data sets.
   - [<b>*Cloud DataProc*</b>](https://cloud.google.com/dataproc)
     - Dataproc is a Managed Spark and Hadoop Service that enables batch processing, querying, streaming and Machine Learning. 
     - Dataproc Automation allows you to easily create clusters, manage them, and save money by turning clusters off when they aren't in use. 
   - [<b>*Cloud DataFusion*</b>](https://cloud.google.com/data-fusion)
     - Cloud Data Fusion is a fully managed, cloud-native enterprise data integration service that allows you to create and maintain data pipelines rapidly. 
     - It also supports a visual point-and-click interface that enables code-free deployment of ETL/ELT data pipelines. 
   - [<b>*Cloud DataComposer*</b>](https://cloud.google.com/composer)
     - Cloud Composer is a fully managed data workflow orchestration tool that lets you write, schedule, and track pipelines. 
     - It is built on the *Apache Airflow* open source project and operated using Python. 
   - [<b>*Cloud DataLab*</b>](https://cloud.google.com/datalab/docs)
     - Cloud Datalab allows you to interactively explore, view, analyze, and transform data using familiar languages like Python and SQL. 
     - You can use notebooks with Python, TensorFlow Machine Learning, and Google Analytics, Google BigQuery, and Google Charts APIs.
   - [<b>*Cloud Dataprep*</b>](https://cloud.google.com/dataprep)
     - Cloud Dataprep is a data service that allows you to explore, clean, and prepare structured and unstructured data in the cloud. 
     - There is no requirement for infrastructure to deploy or manage because Dataprep is serverless and operates at any scale.
     -  
## 8. GCP Data Analysis & Machine Learning Services
   - <b>What is Machine Learning?</b>
     - *Machine learning* is a branch of artificial intelligence (AI) and computer science which focuses on the use of data and algorithms to imitate the way that humans learn, gradually improving its accuracy.
     - Machine learning is an important component of the growing field of data science. 
     - Through the use of statistical methods, algorithms are trained to make classifications or predictions, and to uncover key insights in data mining projects.
     - As big data continues to expand and grow, the market demand for data scientists will increase. 
     - They will be required to help identify the most relevant business questions and the data to answer them.
     - Machine learning algorithms are typically created using frameworks that accelerate solution development, such as TensorFlow and PyTorch.

   - <b>*Types of Machine Learning Systems*</b>
   ![image](https://github.com/novatecstack/gcp-admin-masterclass/assets/121426292/002d4951-4b5a-41f7-9ebb-b9acf8cc6c8a)

 
     - 
   - <b>*Machine Learning Workflow*</b>
   
   
