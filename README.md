Python script by [__Hassan Mojeed__](https://hassanmojeed.pages.dev)<br>
Email: mojeed.o.hassan@gmail.com<br>
Website: [https://hassanmojeed.pages.dev](https://hassanmojeed.pages.dev)




## Introduction

This project intends to use python script to device an ETL (Extract, Transform and Load) Process. The script will fetch excels files from the 
designated directory and conduct some data transformation before loading to Google BigQuery.

## Extraction Phase

We have over 50 excel file formats with each file having exact same data format with the others. Creating a **For Loop** will automate the data extraction.

## Transfromation Phase

Uniformity and standardization is key in any data analysis hence, carefully studying the data shape and data types to ensure that all data in each 
field follow the same format are executed in this phase of the ETL process.

## Loading Phase

The destination data warehouse is the Google BigQuery where further anylysis and insight can be executed. With the help of the Pandas-gbq package this stage was achieved seamlessly.

## Check out the automated Dashbaord [here](https://app.powerbi.com/view?r=eyJrIjoiMGFmYmI4ZmEtYTM3ZS00NzM1LTlhNjItOGNlMGEyNjk4Y2M5IiwidCI6ImFlM2E5OTA2LTc4MWEtNDQ2YS1iZGI2LTYzNzdjMDllMmM2ZiIsImMiOjF9)
