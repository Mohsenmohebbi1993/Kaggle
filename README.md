## kaggle

# 1. toy dataset

This notebook is a gentle tutorial to essential concepts in statistics. I try to present the concepts in a fun and interactive way and I encourage you to play with the code to get a better grasp of the concepts.

# 2. Topic 1. Exploratory data analysis with Pandas

1- Demonstration of main Pandas methods
Well... There are dozens of cool tutorials on Pandas and visual data analysis. If you are already familiar with these topics, you can wait for the 3rd article in the series, where we get into machine learning.  

**[Pandas](http://pandas.pydata.org)** is a Python library that provides extensive means for data analysis. Data scientists often work with data stored in table formats like `.csv`, `.tsv`, or `.xlsx`. Pandas makes it very convenient to load, process, and analyze such tabular data using SQL-like queries. In conjunction with `Matplotlib` and `Seaborn`, `Pandas` provides a wide range of opportunities for visual analysis of tabular data.

The main data structures in `Pandas` are implemented with **Series** and **DataFrame** classes. The former is a one-dimensional indexed array of some fixed data type. The latter is a two-dimensional data structure - a table - where each column contains data of the same type. You can see it as a dictionary of `Series` instances. `DataFrames` are great for representing real data: rows correspond to instances (examples, observations, etc.), and columns correspond to features of these instances.

2- In the field of Machine Learning, *data visualization* is not just making fancy graphics for reports; it is used extensively in day-to-day work for all phases of a project.
- **In this task you should use Pandas to answer a few questions about the [Adult](https://archive.ics.uci.edu/ml/datasets/Adult) dataset. (You don't have to download the data – it's already here). Choose the answers in the [web-form](https://docs.google.com/forms/d/1uY7MpI2trKx6FLWZte0uVh3ULV4Cm_tDud0VDFGCOKg). This is a demo version of an assignment, so by submitting the form, you'll see a link to the solution .ipynb file.**


3- Topic 3. Classification, Decision Trees and k Nearest Neighbors

Before we dive into the material for this week's article, let's talk about the kind of problem that we are going to solve and its place in the exciting field of machine learning. T. Mitchell's book "Machine Learning" (1997) gives a classic, general definition of machine learning as follows: 

> A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E.

In the various problem settings T, P, and E can refer to completely different things. Some of the most popular tasks T in machine learning are the following:

- classification of an instance to one of the categories based on its features;
- regression – prediction of a numerical target feature based on other features of an instance;
- clustering – identifying partitions of instances based on the features of these instances so that the members within the groups are more similar to each other than those in the other groups;
- anomaly detection – search for instances that are "greatly dissimilar" to the rest of the sample or to some group of instances;
- and so many more.

A good overview is provided in the "Machine Learning basics" chapter of ["Deep Learning"](http://www.deeplearningbook.org) (by Ian Goodfellow, Yoshua Bengio, Aaron Courville, 2016).

Experience E  refers to data (we can't go anywhere without it). Machine learning algorithms can be divided into those that are trained in supervised or unsupervised manner. In unsupervised learning tasks, one has a set consisting of instances described by a set of features. In supervised learning problems, there's also a target variable, which is what we would like to be able to predict, known for each instance in a training set. 

## 3 Session 16 - STD Version

Machin learning   
Learn machine learning cootkamp Daneshkarپ

## 4 Descriptive statistics

The National Household <em>Sample Survey - PNAD</em> annually investigates, on a permanent basis, general characteristics of the population, education, work, income and housing and others, with variable frequency, according to the information needs for the country, such as the characteristics on migration, fertility, nuptiality, health, food security, among other topics. The collection of these statistics constitutes, over the 49 years of conducting the research, an important instrument for the formulation, validation and evaluation of policies aimed at socioeconomic development and the improvement of living conditions in Brazil   

## 5 heart attack prediction with machine learning

## 6 Ds Job Post Dea

About Dataset
Context
This is a dataset of data science job posts in glassdoor.

Content
The data was scrapped from glassdoor's website. There are two versions of the data one is uncleaned and another one is cleaned. Web scrapping, Data cleaning & EDA code are added in the code section.

In the cleaned version the columns explanation are as follows,

Job Title: Title of the job posting
Salary Estimation: Salary range for that particular job
Job Description: This contains the full description of that job
Rating: Rating of that post
Company: Name of company
Location: Location of the company
Headquarter: Location of the headquater
Size: Total employee in that company
Type of ownership: Describes the company type i.e non-profit/public/private farm etc
Industry, Sector: Field applicant will work in
Revenue: Total revenue of the company
min_salary,max_salary,avg_salary: Refers to the minimum, maximum and average salary for that post
job_state: State where the applicant will work
same_state: Same state as headquarter or not(Boolean)
company_age: Age of company
python,excel,hadoop,spark,aws,tableau,big_data: Some most appeared skills in boolean columns form
job_simp: Job type
seniority: if job type is senior or not (Boolean)