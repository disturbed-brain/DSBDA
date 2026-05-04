# DSBDAL Lab – Complete Problem Mapping

This repository contains my solutions for all DSBDAL lab problems for TE COMP (2019 pattern).  
Each section below restates the **problem statement in plain words** and points to the **file(s) containing the solution**.

---

## Problem 1 – Data Wrangling I (open dataset)

Use Python and pandas on any open‑source dataset to:

- Import required libraries and load the dataset from the web (with dataset description and source URL).
- Inspect the dataframe: shape, basic statistics, and missing values.
- Describe each variable (meaning, type) and summarize variable types (numeric, categorical, etc.).
- Fix incorrect data types, normalize / scale numeric features, and convert categorical variables to numeric codes.[file:1]

**Solution file**

- `Assignment1.ipynb`

---

## Problem 2 – Data Wrangling II (academic performance)

Create an “academic performance” dataset for students and:

- Detect and handle missing values and inconsistencies.
- Scan numeric variables for outliers and treat them with a suitable technique (e.g. IQR‑based removal).[file:1]
- Apply at least one data transformation (e.g. scaling, log transform) with a clear reason: improving scale, linearising relations, or reducing skewness toward a normal distribution.

**Solution file**

- `dsbda 2.pdf`  – screenshots of the Colab notebook that creates and cleans the dataset.

---

## Problem 3 – Descriptive statistics and Iris summary

On a numeric dataset:

- Compute grouped descriptive statistics (mean, median, min, max, standard deviation, percentiles, etc.) for one or more numeric variables, grouped by a categorical variable (e.g. income grouped by age group).[file:1]
- Build a representation that associates a numeric list with each category.
- For the Iris dataset, compute and display basic statistics (percentiles, mean, standard deviation, etc.) separately for each species.

**Solution file**

- `Assignment3.ipynb`

---

## Problem 4 – Data Analytics I (Linear Regression – Boston Housing)

Build a regression model to predict house prices using the Boston Housing dataset:

- Load the dataset (14 features, 506 rows) and explain the key features.
- Split into training and test sets.
- Train a linear regression model to predict house price from the given features.
- Evaluate the model (e.g. mean squared error, \(R^2\)) and comment briefly on the performance.[file:1]

**Solution file**

- `Assignment4.ipynb`
- Dataset: `Boston.csv`

---

## Problem 5 – Data Analytics II (Logistic Regression – Social_Network_Ads)

On the `Social_Network_Ads.csv` dataset:

- Implement logistic regression (Python) to perform binary classification.[file:1]
- Compute the confusion matrix and derive TN, FP, FN, TP.
- Calculate accuracy, error rate, precision, and recall.

**Solution file**

- `Assignment5.ipynb`
- Dataset: `Social_Network_Ads.csv`

---

## Problem 6 – Data Analytics III (Naive Bayes – Iris)

On the Iris dataset:

- Implement a simple Naive Bayes classifier in Python.
- Evaluate on a test set.
- Compute confusion matrix and derive TN, FP, FN, TP along with accuracy, error rate, precision, and recall.[file:1]

**Solution file**

- `Assignment6.ipynb`
- Dataset: `iris.csv`

---

## Problem 7 – Text Analytics (pre‑processing + TF‑IDF)

For a sample text document:

- Apply document preprocessing steps: tokenization, part‑of‑speech (POS) tagging, stop‑word removal, stemming, and lemmatization.
- Build a numerical representation of the document using term frequency (TF) and inverse document frequency (IDF / TF‑IDF).[file:1]

**Solution file**

- `Assignment7.ipynb`

---

## Problem 8 – Data Visualization I (Titanic patterns and fare histogram)

Using the inbuilt Titanic dataset (around 891 passengers):

- Use Seaborn to explore patterns in the data (e.g. survival vs class, sex, age).
- Plot a histogram showing how passenger ticket fare is distributed.[file:1]

**Solution file**

- `Assignment9dsbda.ipynb`
- Dataset: `Titanic-Dataset.csv` (and/or Seaborn `titanic`)

---

## Problem 9 – Data Visualization II (Titanic age vs sex vs survival)

On the same Titanic dataset:

- Plot a boxplot of passenger age for each gender, with survival status as an additional factor (age vs `sex` with a `survived` hue).[file:1]
- Write textual observations explaining what the boxplot suggests about survival in relation to age and gender.

**Solution file**

- `Assignment9dsbda.ipynb`
- Dataset: `Titanic-Dataset.csv`

---

## Problem 10 – Data Visualization III (Iris histograms and boxplots)

Using the Iris dataset:

- List all features (sepal length/width, petal length/width, species) and classify each as numeric or nominal (categorical).
- Plot a histogram for each numeric feature to show its distribution.
- Plot a boxplot for each numeric feature, compare the distributions, and identify outliers.[file:1]

**Solution file**

- `Assignment10.ipynb`
- Dataset: `iris.csv`

---

## Problem 11 – Hadoop MapReduce log analysis (HDFS)

Design a MapReduce application that processes a system log file and:

- Reads records describing user logins with time spent.
- Computes the total login time for each user.
- From the output, identify which user(s) logged in for the maximum total duration.[file:29]

**Solution file**

- `Assignment-11.pdf` – contains `LogMapper`, `LogReducer`, `LogDriver` code and execution screenshots.

---

## Problem 12 – Hadoop MapReduce weather analysis + Scala Spark program

### 12(a) Weather data – hottest year using MapReduce

Design a MapReduce application that:

- Reads weather data records containing year and temperature.
- For each year, computes the maximum temperature observed.
- From the results, identify the hottest year(s).[file:31]

**Solution file**

- `Assignment-12.pdf` – contains `WeatherMapper`, `WeatherReducer`, `WeatherDriver` code and execution screenshots.

### 12(b) Simple Scala program using Apache Spark

Write a simple Scala program using Apache Spark (local mode):

- Read a text file from HDFS or local file system.
- Perform the classic WordCount task: split lines into words, count occurrences of each word, and save the result back as text.[file:1]

**Solution file**

- `dsbda 12.pdf` – Scala + Spark WordCount implementation.

---

## Notes

- All problem statements above are paraphrased from the official DSBDAL lab manual and department handouts; see the attached PDFs for the exact wording.[file:1][file:29][file:31]
- This README is meant to make it obvious for evaluators: **for any problem number, they can immediately see which file contains the solution.**
