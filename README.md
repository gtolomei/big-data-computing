# Big Data Computing (2023-2024)

[News](#News) | [General Information](#General-Information) | [Syllabus](#Syllabus) | [Class Schedules](#Class-Schedules) | [Previous Years](#Previous-Years)

## News
- Starting this year, the Big Data Computing course has been moved to the first semester and divided into **two distinct modules**, each one carrying 3 CFUs (credits). [Prof. Daniele De Sensi](https://corsidilaurea.uniroma1.it/it/users/danieledesensiuniroma1it) will lead the first module, while the second module (i.e., _this_ module) will be under my instruction. Importantly, these modules will **not** run concurrently; once the first module concludes, the second will begin. The estimated start date for this module is expected to be in the first week of November. We will provide more precise information as the conclusion of the first module approaches.

## General Information

Welcome to the Big Data Computing class!

This is a first-semester course of the [MSc in Computer Science at the Sapienza University of Rome](https://www.studiareinformatica.uniroma1.it/master-course-computer-science).

This repository contains class material along with any useful information for the 2023-2024 academic year.

### Class Schedule
- **Tuesday** from **2:00 p.m.** to **4:00 p.m.** in Aula Magna - "Building C" at Viale Regina Elena 295
- **Wednesday** from **10:00 a.m.** to **1:00 p.m.** in Aula Magna - "Building C" at Viale Regina Elena 295

### Moodle Web Page
Students must subscribe to the Moodle web page using the same credentials (username/password) to access the Wi-Fi network and Infostud services at the following link: https://elearning.uniroma1.it/course/view.php?id=17115

### Contacts
- Email: tolomei@di.uniroma1.it
- Website: https://www.di.uniroma1.it/~tolomei
- Bacheca Sapienza: https://corsidilaurea.uniroma1.it/it/users/gabrieletolomeiuniroma1it

### Office Hours
Please drop me a message at <a href="mailto:tolomei@di.uniroma1.it">tolomei@di.uniroma1.it</a> in case you would like to schedule a meeting, either online (i.e., via Google Meet or Zoom) or in-person (i.e., in Room 106 located at the 1st floor of Building E in Viale Regina Elena 295).

### Description and Goals
The amount, variety, and rate at which data is being generated nowadays, both by humans and machines, are unprecedented. This opens up a number of challenges on dealing with those data, as traditional computing paradigms are not conceived to operate at such a scale.

"Big Data" is the umbrella term that has rapidly become popular to describe methodologies and tools specifically designed for collecting, storing, and processing very large or complex data sets. In addition to addressing foundational computer science problems, such as searching and sorting, big data computing mainly focuses on extracting knowledge - thereby value - from large-scale data sets using advanced data analysis techniques, such as machine learning.

This course is intended to provide graduate-level students with a deep understanding of programming models and tools that are suitable for the large-scale analysis of data distributed across clusters of computers. More specifically, the course will give students the ability to proficiently develop big data/machine learning solutions on top of industry-standard frameworks, such as Hadoop and Spark, to tackle real-world problems faced by the so-called "Big Five" tech companies (i.e., Apple, Amazon, Google, Microsoft, and Facebook): text/graph analysis, classification/regression, and recommendation, just to name a few.

### Prerequisites
The course assumes that students are familiar with the basics of data analysis and machine learning, properly supported by a strong knowledge of foundational concepts of calculus, linear algebra, probability, and statistics. In addition, students must have non-trivial computer programming skills (preferably using Python programming language). Previous experience with Hadoop, Spark, or distributed computing is not required.

### Exams
**TBA**

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

## Syllabus:

<!--**Introduction**
- The Big Data Phenomenon
- The Big Data Infrastructure
    - Distributed File Systems (HDFS)
    - MapReduce (Hadoop)
    - Spark
- PySpark + Databricks

**Unsupervised Learning: Clustering**
- The Curse of Dimensionality (Similarity Measures)
- Algorithms: K-means
- Example: Document Clustering

**Dimensionality Reduction**
- Feature Extraction
- Algorithms: Principal Component Analysis (PCA)
- Example: PCA + Handwritten Digit Recognition

**Supervised Learning**
- Basics of Machine Learning
- Regression/Classification
- Algorithms: Linear Regression/Logistic Regression/Random Forest
- Examples: 
    - Linear Regression -> House Pricing Prediction (i.e., predict the price which a house will be sold)
    - Logistic Regression/Random Forest -> Marketing Campaign Prediction (i.e., predict whether a customer will subscribe a term deposit of a bank)

**Recommender Systems**
- Content-based vs. Collaborative filtering
- Algorithms: k-NN, Matrix Factorization (MF)
- Example: Movie Recommender System (MovieLens)

**Graph Analysis**
- Link Analysis
- Algorithms: PageRank
- Example: Ranking (a sample of) the Google Web Graph

**Anything Else?**
- ...
-->
<hr>

## Class Schedules

| Lecture \#  | Date       | Topic                                         | Material        | 
|-------------|------------|-----------------------------------------------|-----------------|
<!--| Lecture 1   | 02/27/2023 | Introduction to Big Data: Motivations and Challenges | [slides: <a href="./slides/01_Intro.pdf" target="_blank">PDF</a>] |
| Lecture 2   | 02/28/2023 | MapReduce Programming Model | [slides: <a href="./slides/02_MapReduce.pdf" target="_blank">PDF</a>] |
| Lecture 3   | 03/06/2023 | Apache Spark | [slides: <a href="./slides/03_Spark.pdf" target="_blank">PDF</a>] |
| Lecture 4   | 03/07/2023 | PySpark Tutorial | [notebook: <a href="./notebooks/PySpark_Tutorial.ipynb" target="_blank">ipynb</a>] |
| Lecture 5  | 03/13/2023 | The Curse of Dimensionality | [slides: <a href="./slides/05_The_Curse_of_Dimensionality.pdf" target="_blank">PDF</a>, notebook: <a href="./notebooks/The_Curse_of_Dimensionality.ipynb" target="_blank">ipynb</a>] |
| Lecture 6 | 03/14/2023 | Clustering Algorithms (Part I): K-means | [slides: <a href="./slides/06-07_Clustering_Algorithms.pdf" target="_blank">PDF</a>] |
| Lecture 7 | 03/20/2023 | Clustering Algorithms (Part II): Validity Measures | [slides: <a href="./slides/06-07_Clustering_Algorithms.pdf" target="_blank">PDF</a>] |
| Lecture 8   | 03/21/2023 | Document Clustering with PySpark | [slides: <a href="./slides/08_Document_Clustering.pdf" target="_blank">PDF</a>, notebook: <a href="./notebooks/Document_Clustering.ipynb" target="_blank">ipynb</a>] |
| Lecture 9   | 03/27/2023 | Dimensionality Reduction: Principal Component Analysis (Part I) | [slides: <a href="./slides/09_Dimensionality_Reduction_(Principal_Component_Analysis_Part_I).pdf" target="_blank">PDF</a>] |
| Lecture 10   | 03/28/2023 | Dimensionality Reduction: Principal Component Analysis (Part II) | [slides: <a href="./slides/10_Dimensionality_Reduction_(Principal_Component_Analysis_Part_II).pdf" target="_blank">PDF</a>, notes: <a href="./extra/Notes_on_Principal_Component_Analysis.pdf" target="_blank">PDF</a>, notebook: <a href="./notebooks/Principal_Component_Analysis.ipynb" target="_blank">ipynb</a>] |
| Lecture 11  | 04/03/2023 | Supervised Learning (Part I): Data Preparation | [slides: <a href="./slides/11_Supervised_Learning_(Part_I).pdf" target="_blank">PDF</a>] |
| Lecture 12  | 04/04/2023 | Supervised Learning (Part II): Model Training | [slides: <a href="./slides/12_Supervised_Learning_(Part_II).pdf" target="_blank">PDF</a>] |
| Lecture 13  | 04/17/2023 | Linear Regression (OLS): Part I | [slides: <a href="./slides/13_Linear_Regression.pdf" target="_blank">PDF</a>] |
| Lecture 14  | 04/18/2023 | Linear Regression (OLS): Part II | [slides: <a href="./slides/13_Linear_Regression.pdf" target="_blank">PDF</a>], notebook: <a href="./notebooks/Linear_Regression.ipynb" target="_blank">ipynb</a>] |
| Lecture 15  | 04/24/2023 | Logistic Regression: Part I | [slides: <a href="./slides/14_Logistic_Regression.pdf" target="_blank">PDF</a>], notes: <a href="./extra/Notes_on_Logistic_Regression.pdf" target="_blank">PDF</a>] |
| Lecture 16  | 05/02/2023 | Logistic Regression: Part II (Gradient Descent) | [slides: <a href="./slides/15_Gradient_Descent.pdf" target="_blank">PDF</a>] |
| Lecture 17  | 05/08/2023 | Decision Trees and Ensembles (Part I) | [slides: <a href="./slides/16_Decision_Trees_and_Ensembles_(Part_I).pdf" target="_blank">PDF</a>]|
| Lecture 18  | 05/09/2023 | Decision Trees and Ensembles (Part II) | [slides: <a href="./slides/17_Decision_Trees_and_Ensembles_(Part_II).pdf" target="_blank">PDF</a>]|
| Lecture 18 (extra)  | 05/09/2023 | Evaluation Metrics for Classification | [slides: <a href="./slides/18_Evaluation_Metrics_for_Classification.pdf" target="_blank">PDF</a>, notebook: <a href="./notebooks/Classification.ipynb" target="_blank">ipynb</a>]|
| Lecture 19  | 05/15/2023 | Recommender Systems (Part I) | [slides: <a href="./slides/19_Recommender_Systems_(Part_I).pdf" target="_blank">PDF</a>]|
| Lecture 20  | 05/16/2023 | Recommender Systems (Part II) | [slides: <a href="./slides/20_Recommender_Systems_(Part_II).pdf" target="_blank">PDF</a>]|
| Lecture 21  | 05/22/2023 | Recommender Systems (Part III) | [slides: <a href="./slides/21_Recommender_Systems_(Part_III).pdf" target="_blank">PDF</a>], notebook: <a href="./notebooks/MF_Recommender_Systems.ipynb" target="_blank">ipynb</a>]|
| Lecture 22  | 05/23/2023 | Graph Link Analysis | [slides: <a href="./slides/22_Graph_Link_Analysis.pdf" target="_blank">PDF</a>]|
| Lecture 25  | 05/25/2022 | PageRank | [slides: <a href="./slides/25_PageRank.pdf" target="_blank">PDF</a>, notes: <a href="./extra/Notes_on_PageRank.pdf" target="_blank">PDF</a>]|, notebook: <a href="./notebooks/PageRank.ipynb" target="_blank">ipynb</a>]|
| ----------  | 05/25/2022 | The Last Take Home Message | [slides: <a href="./slides/The_Last_Take_Home_Message.pdf" target="_blank">PDF</a>]|
-->
<hr>

# Previous Years
In the following, you can quickly navigate through Big Data Computing class information and material from previous years.

**NOTE:** _The folder containing the class material is **unique**, and it is subject to changes and/or updates; as such, there may be differences between the content displayed on this website and what has been shown in class in the past._

-   [2019-20](./oldest/2019-20.md)
-   [2020-21](./oldest/2020-21.md)
-   [2021-22](./oldest/2021-22.md)
-   [2022-23](./oldest/2022-23.md)
