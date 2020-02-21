# Big Data Computing

## General Information

Welcome to the Big Data Computing class!

This is a first-year, second-semester course of the [MSc in Computer Science of Sapienza University of Rome](https://www.studiareinformatica.uniroma1.it/master-course-computer-science).

This repository contains class material along with any useful information for the current academic year (2019/20).

### Class Schedule
- **Tuesday** from **8:00AM** to **10:00AM** (Room Alfa, via Salaria 113)
- **Wednesday** from **3:00PM** to **6:00PM** (Room Alfa, via Salaria 113)

### Office Hours
- **Tuesday** from **2:00PM** to **4:00PM**, Room G39 located at the 2nd floor of Building G in viale Regina Elena 295

### Description and Goals
The amount, variety, and rate at which data is being generated nowadays both by humans and machines are unprecedented. This opens up a number of challenges on how to deal with those data, as traditional computing paradigms are not conceived to operate at such a scale.

"Big Data" is the umbrella term that has rapidly become popular to describe methodologies and tools specifically designed for collecting, storing, and processing very large or complex data sets. In addition to addressing foundational computer science problems, such as searching and sorting, big data computing mainly focuses on extracting knowledge - thereby value - from large-scale data sets using advanced data analysis techniques, such as machine learning.

This course is intended to provide graduate-level students with a deep understanding of programming models and tools that are suitable for the large-scale analysis of data distributed across clusters of computers. More specifically, the course will give students the ability to proficiently develop big data/machine learning solutions on top of industry standard frameworks, such as Hadoop and Spark, to tackle real-world problems faced by the so-called "Big Five" tech companies (i.e., Apple, Amazon, Google, Microsoft, and Facebook): text/graph analysis, classification/regression, and recommendation, just to name a few.

### Prerequisites
The course assumes that students are familiar with the basics of data analysis and machine learning, properly supported by a strong knowledge of foundational concepts of calculus, linear algebra, and probability and statistics. In addition, students must have non-trivial computer programming skills (preferably using Python programming language). Previous experience with Hadoop, Spark, or distributed computing is not required.

### Exams
Students must prove their level of comprehension of the subject by developing a software project, leveraging the set of methodologies and tools introduced during classes. Projects must of course refer to typical Big Data tasks: e.g., clustering, prediction, recommendation using very-large datasets in _any_ application domain of interest. The topic of the project must anyway be agreed with the teacher in advance; references where to select interesting projects from will be however suggested throughout the course (e.g., [Kaggle](https://www.kaggle.com/)).
Projects can be done either **individually** or in group of **at most 2 students**, and they should be accompanied by a brief presentation written in english (e.g., a few PowerPoint slides). Finally, there will be an oral exam where submitted projects will be discussed in english; other questions on _any_ topic addressed during the course may also be asked, but this can be done either in english or in italian.

### Recommended Textbooks
No textbooks are mandatory to successfully follow this course. However, there is a huge set of references which may be worth mentioning, especially to those who wants to dig deeper into some specific topics. Among those, some readings I would like to suggest are as follows:
- _Mining of Massive Datasets_ [Leskovec, Rajaraman, Ullman] [available online](http://infolab.stanford.edu/~ullman/mmds/book.pdf).
- _Big Data Analysis with Python_ [Marin, Shukla, VK]
- _Large Scale Machine Learning with Python_ [Sjardin, Massaron, Boschetti]
- _Spark: The Definitive Guide_ [Chambers, Zaharia]
- _Learning Spark: Lightning-Fast Big Data Analysis_ [Karau, Konwinski, Wendell, Zaharia]
- _Hadoop: The Definitive Guide_ [White]
- _Python for Data Analysis_ [Mckinney]
 
<hr>

## Syllabus
**Introduction**
- The Big Data Phenomenon
- The Big Data Infrastructure
    - Distributed File Systems (HDFS)
    - MapReduce (Hadoop)
    - Spark

**Unsupervised Learning: Clustering**
- Similarity Measures
- Algorithms: K-means
- Example: Document Clustering (_to be confirmed_)

**Supervised Learning**
- Basics of Machine Learning
- Regression/Classification
- Algorithms: Linear Regression/Logistic Regression/Random Forest
- Example: Crime Rate Prediction (_to be confirmed_)

**Recommender Systems**
- Content-based vs. Collaborative filtering
- Algorithms: k-NN, SVD (matrix factorization)
- Example: MovieLens (_to be confirmed_)

**Graph Analysis**
- Social Network Analysis
- Graph Metrics
- Algorithms: PageRank
- Example: Link Prediction (_to be confirmed_)

**Real-time Analytics**
- Stream Processing
- Example: Stock Market Forecasting (_to be confirmed_)

<hr>

## Class Material

| Lecture \# | Date | Topic                                     | Materiale      | 
|------------|------|-----------------------------------------------|----------------|
| Lecture 1  | 02/25/2020 | Introduction to Big Data | [slides: <a href="./lectures/slides/01_Intro.pdf" target="_blank" onclick="return false;">PDF</a>] |
