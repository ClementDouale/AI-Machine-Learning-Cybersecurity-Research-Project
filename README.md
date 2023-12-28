# Automated Train Cybersecurity Assessment AI
## Overview
This project focuses on leveraging AI to determine cybersecurity levels for automated train systems using the Common Vulnerabilities and Exposures (CVE) dataset. The CVE dataset contains multiple columns, each providing information about a security flaw identified by its Common Weakness Enumeration (CWE) name. CWE is a list of vulnerabilities commonly found in software. Each flaw's risk is defined by a CVSS score ranging from 0 to 10, where 0 represents low risk, and 10 signifies critical risk. The CVSS, or Common Vulnerability Scoring System, offers a standardized evaluation of vulnerability criticality based on objective and measurable criteria.

## Approach
The approach in this notebook addresses the problem in two ways:

## Regression
Attempting to predict the exact CVSS score.

## Classification
Grouping CVSS scores into classes (e.g., LOW, MEDIUM, HIGH, CRITICAL) based on their values.

For this notebook, we'll adopt the regression approach to minimize the loss of information caused by dividing scores into classes.

## Data Preparation
Before using the data in this notebook, extensive data cleaning is necessary within the Excel file to remove randomly added comments and standardize the number of columns. More than 2000 lines have been manually removed to ensure data integrity.

## Dataset
The dataset, named CVE, is available here. It comprises multiple columns, each providing information on a security flaw identified by its CWE name. Each flaw's risk is represented by a CVSS score, enabling the assessment of cybersecurity levels in automated train systems.

## Approach Details
Data Cleaning
Prior to utilization in this notebook, extensive cleaning is required to standardize the dataset, remove random comments, and ensure data consistency.

## Regression Model
The notebook employs a regression model to predict the exact CVSS score, facilitating a more granular understanding of cybersecurity risks.

## Usage
Download Dataset:
Obtain the CVE dataset from the provided link.

## Data Preparation:
Perform necessary cleaning and standardization of the dataset as described in the notebook.

## Run the Notebook:
Execute the notebook file to train and test the regression model.
