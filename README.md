# IoT-Analysis
Implement a complete real-time data analysis solution using Apache Spark and Apache Kafka<br>
<br>
![image](https://user-images.githubusercontent.com/111542025/235742547-0bb11f1a-3c05-44a9-815b-198ed556dc3d.png)

## This is the 1st version

## Business Problem
> Data sources: The [database](https://github.com/Caio-Felice-Cunha/IoT-Analysis/blob/main/data__sensors.txt) was created through a script that simulates the data of a machine. Such a script was developed by the Data Science Academy team.
<br>

We will collect data from IoT (Internet of Things) sensors and, in real time (as the data is generated and collected), perform the analysis work and deliver the answer to a given business problem.<br>

A certain sporting goods industry has several pieces of equipment in the company's industrial park used for production and operating 24/7.<br>

Each equipment has a sensor that measures the temperature at regular intervals. Equipment that exceeds a certain average temperature for a long time may have a reduced useful life, generating additional maintenance costs or equipment replacement.<br>

The operations department would like to have a real-time data analysis solution that calculates the average temperature of each piece of equipment from the reading of data emitted by IoT sensors at regular intervals.<br>

The main objective of these projects is to demonstrate the power of Machine Learning in business.

## Solution Strategy
The projects were made in Apache Spark and Apache Kafka, as well as other packages in Python.
* Step 01: Create a script to simulate data coming from a machine via streaming;
* Step 02: Configure Kafka;
* Step 03: Connect to the data source;
* Step 04: Constantly generate data so that analysis can take place;
* Step 05: Run the analysis script while producing data.


## Next Steps
* Make more Analysis.

## Disclaimer
This project was largely done in the Data Science Academy, Big Data Real-Time Analytics with Python and Spark course (part of the Data Scientist training)
