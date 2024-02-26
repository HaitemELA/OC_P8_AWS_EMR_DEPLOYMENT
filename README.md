# OC_P8_AWS_EMR_DEPLOYMENT

# Fruits! AgriTech - Image Processing Pipeline
## Overview

##Project Structure
### 1. Data
We have a dataset consisting of fruit images and their associated labels. You can download the dataset here. This dataset has been used by a former intern in an AWS EMR (Elastic MapReduce) environment, and their notebook will serve as the starting point for our data processing pipeline.

### 2. Mission
Your mission, as a Data Scientist at Fruits! AgriTech, is to build upon the intern's work and complete the data processing pipeline. It is crucial to focus on setting up the initial components that will scale effectively with the growing volume of data.

### 3. Constraints
Before you proceed, please be aware of the following constraints:

Develop scripts in Pyspark and utilize AWS Cloud services (EMR, S3, IAM).

Optionally, consider transferring the processes to Databricks.

Demonstrate the setup of an operational EMR instance.

Explain the PySpark script step-by-step, including the distribution of TensorFlow Keras model weights.

Implement a PCA (Principal Component Analysis) dimensionality reduction step in PySpark.

Ensure GDPR compliance by configuring the installation to use servers located in the European territory.

Provide a critical evaluation of the solution before considering generalization.

Keep the EMR instance operational only for testing and demos to manage costs (aiming to stay under 10 euros for reasonable usage).

Use a local server for updating the PySpark script to reduce EMR costs.
