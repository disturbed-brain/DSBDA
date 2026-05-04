# DSBDAL Lab – Problem Statements and Solutions

This repository contains my solutions for all DSBDAL lab problems (TE COMP, 2019 pattern).  
Each section below lists the official **problem title** and a brief description taken from the lab manual, followed by the **file containing the solution**.[DSBDAL-problem-statements.docx.pdf][file:33]

---

## 1. Data Wrangling I

**Official title:** Data Wrangling I – Perform the following operations using Python on any open source dataset (e.g., data.csv).[file:33]

**What it asks (short):**

- Import libraries and load an open‑source dataset from the web, with description and URL.  
- Do basic EDA: shape, `describe()`, missing values, variable descriptions and types.  
- Normalize / format data, fix data types, and convert categorical variables to quantitative form, explaining each step.[file:33]

**Solution file:** `Assignment1.ipynb`

---

## 2. Data Wrangling II

**Official title:** Data Wrangling II – Create an “Academic performance” dataset of students and perform the following operations using Python.[file:33]

**What it asks (short):**

- Scan all variables for missing values / inconsistencies and treat them appropriately.  
- Detect numeric outliers and handle them with a suitable method.  
- Apply at least one transformation to change scale / linearize / reduce skewness, and document the reasoning.[file:33]

**Solution file:** `dsbda 2.pdf`

---

## 3. Descriptive Statistics – Measures of Central Tendency and Variability

**Official title:** Descriptive Statistics – Measures of Central Tendency and variability.[file:33]

**What it asks (short):**

- For a numeric dataset (e.g., age, income), compute mean, median, min, max, standard deviation etc., **grouped by a categorical variable**, and represent values per category.[file:33]  
- For `iris.csv`, display basic statistics (percentiles, mean, standard deviation, etc.) for each species (`Iris-setosa`, `Iris-versicolor`, `Iris-virginica`).[file:33]

**Solution file:** `Assignment3.ipynb`

---

## 4. Data Analytics I

**Official title:** Data Analytics I – Create a Linear Regression Model using Python/R to predict home prices using Boston Housing Dataset.[file:33]

**What it asks (short):**

- Use the Boston Housing dataset (506 samples, 14 features).  
- Build a linear regression model to predict house prices from the features, and evaluate the model (e.g., error and \(R^2\)).[file:33]

**Solution file:** `Assignment4.ipynb` (dataset: `Boston.csv`)

---

## 5. Data Analytics II

**Official title:** Data Analytics II – Implement logistic regression using Python/R to perform classification on Social_Network_Ads.csv dataset.[file:33]

**What it asks (short):**

- Train a logistic regression classifier on `Social_Network_Ads.csv`.  
- Compute the confusion matrix and derive TP, FP, TN, FN, Accuracy, Error rate, Precision, Recall.[file:33]

**Solution file:** `Assignment5.ipynb` (dataset: `Social_Network_Ads.csv`)

---

## 6. Data Analytics III

**Official title:** Data Analytics III – Implement Simple Naïve Bayes classification algorithm using Python/R on iris.csv dataset.[file:33]

**What it asks (short):**

- Train a Naive Bayes classifier on `iris.csv`.  
- Compute a confusion matrix and the same metrics as above: TP, FP, TN, FN, Accuracy, Error rate, Precision, Recall.[file:33]

**Solution file:** `Assignment6.ipynb` (dataset: `iris.csv`)

---

## 7. Text Analytics

**Official title:** Text Analytics.[file:33]

**What it asks (short):**

1. Take a sample document and perform preprocessing: Tokenization, POS Tagging, stop‑words removal, Stemming, and Lemmatization.  
2. Build a document representation by computing Term Frequency and Inverse Document Frequency (TF, IDF / TF‑IDF).[file:33]

**Solution file:** `Assignment7.ipynb`

---

## 8. Data Visualization I

**Official title:** Data Visualization I.[file:33]

**What it asks (short):**

1. Use the inbuilt `titanic` dataset (891 passengers) and Seaborn to explore patterns in the data.  
2. Plot a histogram showing how the ticket price (`fare`) is distributed for passengers.[file:33]

**Solution file:** `Assignment9dsbda.ipynb` (dataset: `Titanic-Dataset.csv` or Seaborn `titanic`)

---

## 9. Data Visualization II

**Official title:** Data Visualization II.[file:33]

**What it asks (short):**

- Using the same `titanic` dataset, plot a **boxplot of age distribution** for each gender with survival information (columns `sex`, `age`, `survived`).  
- Write observations explaining what the plot shows.[file:33]

**Solution file:** `Assignment9dsbda.ipynb`

---

## 10. Data Visualization III

**Official title:** Data Visualization III.[file:33]

**What it asks (short):**

- Download the Iris dataset into a DataFrame.  
1. List all features and specify their types (numeric vs nominal).  
2. Draw a histogram for each feature to show distributions.  
3. Draw a boxplot for each feature, compare distributions, and identify outliers.[file:33]

**Solution file:** `Assignment10.ipynb` (dataset: `iris.csv`)

---

## 11. Hadoop MapReduce – WordCount in Java

**Official title:** Write a code in JAVA for a simple WordCount application that counts the number of occurrences of each word in a given input set using the Hadoop MapReduce framework on local‑standalone set‑up.[file:33]

**What it asks (short):**

- Implement the classic WordCount MapReduce job in Java.  
- Run it on a local / standalone Hadoop setup and count occurrences of each word in an input text.[file:33]

**Solution file (department variant):**

- `Assignment-11.pdf` – Java MapReduce code and run screenshots for log‑file analysis (same MapReduce pattern; can be used to demonstrate WordCount‑style aggregation).

*(If you also add a pure WordCount Java code file, mention it here.)*

---

## 12. Simple Program in Scala using Apache Spark

**Official title:** Write a simple program in SCALA using Apache Spark framework.[file:33]

**What it asks (short):**

- Implement a basic Scala application using the Spark framework (e.g., reading a text file, transforming data, and writing results).[file:33]

**Solution files:**

- `dsbda 12.pdf` – Scala + Spark WordCount implementation (reads text, counts words, writes output).  
- `Assignment-12.pdf` – Java MapReduce program for weather data (department‑specific extension; finds maximum temperature per year).

---

## How to Use This Repo

For each problem:

1. Read the **official statement** in `DSBDAL-problem-statements.docx.pdf`.  
2. Open the **corresponding file** listed above (`AssignmentX.ipynb`, `Assignment-11.pdf`, `Assignment-12.pdf`, `dsbda 2.pdf`, `dsbda 12.pdf`).  
3. Run the notebook or review the code/output as needed.

This README is intentionally one‑to‑one with the official DSBDAL problem sheet so evaluators can quickly verify which file solves which problem.[file:33]
