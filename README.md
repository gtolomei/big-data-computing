# Big Data Computing (2023-2024)

[News](#News) | [General Information](#General-Information) | [Syllabus](#Syllabus) | [Class Schedules](#Class-Schedules) | [Previous Years](#Previous-Years)

## News
- **January 22, 2024 Exam Session**: The seminar session is scheduled for **Monday, January 22, 2024**, and will be held in "Sala riunioni" (Room 305, 3rd Floor) in Building E, Viale Regina Elena 295, starting at **9:30 a.m.** For those unable to attend in person, remote participation is available via the following Zoom link: https://uniroma1.zoom.us/my/desensi
- **January and February 2024 Exam Sessions**<br/>
Registrations for the January and February 2024 exam sessions are open on Infostud. There are **four** distinct dates you can pick from:
    - January 22 (id **914699**)
    - January 31 (id **914701**)
    - February 7 (id **914702**)
    - February 14 (id **914703**)
- **ANNOUNCEMENT:** There will be **no class on Wednesday, December 6**, due to the [IT Meeting event](https://itmeeting.wordpress.com/), which you are all welcome to join.
- Starting this year, the Big Data Computing course has been moved to the first semester and divided into **two distinct modules**, each one carrying 3 CFUs (credits).<br/>
[Prof. Daniele De Sensi](https://corsidilaurea.uniroma1.it/it/users/danieledesensiuniroma1it) will lead the first module, while the second module (i.e., _this_ module) will be under my instruction.<br/>
Importantly, these modules will **not** run concurrently; once the first module concludes, the second will begin. The estimated start date for this module is expected to be in the first week of November. We will provide more precise information as the conclusion of the first module approaches.

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
Starting this year, the exam will consist of a **seminar on a research paper** chosen from a curated list of distinguished conferences and journals that align with the topics covered in the course.<br/>
Since selecting a paper that simultaneously covers both units can be challenging, you can choose a research work that prevalently concerns one of the two units. For example, you can select work on big data architectures (first unit) or high-dimensional data representation learning (second unit).<br/>
Each seminar can be done **individually** or in a **group of at most two students**.<br/>
A document containing the main guidelines for the final exam is available [here](./extra/Final_Exam_Guidelines.pdf).

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

**Introduction**
- The Big Data Phenomenon
- Motivation and Challenges
- The Curse of Dimensionality

**Unsupervised Learning: Clustering**
- Algorithms: K-means

**Dimensionality Reduction**
- Algorithms: Principal Component Analysis (PCA)

**Recommender Systems**
- Algorithms: k-NN, Matrix Factorization (MF)

**Graph Analysis**
- Algorithms: PageRank

**Anything Else?**
- ...
<hr>

## Class Schedules

| Lecture \#  | Date       | Topic                                         | Material        | 
|-------------|------------|-----------------------------------------------|-----------------|
| Lecture 1   | 11/21/2023 | Introduction to Big Data: Motivations and Challenges | [slides: <a href="./slides/Introduction.pdf" target="_blank">PDF</a>] |
| Lecture 2   | 11/22/2023 | The Curse of Dimensionality | [slides: <a href="./slides/The_Curse_of_Dimensionality.pdf" target="_blank">PDF</a>, notebook: <a href="./notebooks/The_Curse_of_Dimensionality.ipynb" target="_blank">ipynb</a>] |
| Lecture 3 | 11/28/2023 | Clustering: A General Framework | [slides: <a href="./slides/Clustering.pdf" target="_blank">PDF</a>] |
| Lecture 4 | 11/29/2023 | Clustering: K-means | [slides: <a href="./slides/K-means.pdf" target="_blank">PDF</a>] |
| Lecture 5 | 12/05/2023 | Dimensionality Reduction: Principal Component Analysis (Part I) | [slides: <a href="./slides/Dimensionality_Reduction_(Principal_Component_Analysis_Part_I).pdf" target="_blank">PDF</a>, notes: <a href="./extra/Notes_on_Principal_Component_Analysis.pdf" target="_blank">PDF</a>] |
| Lecture 6 | 12/12/2023 | Dimensionality Reduction: Principal Component Analysis (Part II) | [slides: <a href="./slides/Dimensionality_Reduction_(Principal_Component_Analysis_Part_II).pdf" target="_blank">PDF</a>] |
| Lecture 7  | 12/13/2023 | Recommender Systems (Content-based) [Part I & II] | [slides: <a href="./slides/Recommender_Systems_(Part_I).pdf" target="_blank">PDF(I)</a>, <a href="./slides/Recommender_Systems_(Part_II).pdf" target="_blank">PDF(II)</a>]|
| Lecture 8  | 12/19/2023 | Recommender Systems (Collaborative Filtering) [Part III] | [slides: <a href="./slides/Recommender_Systems_(Part_III).pdf" target="_blank">PDF(III)</a>]|
| Lecture 10  | 12/20/2023 | PageRank | [slides: <a href="./slides/PageRank.pdf" target="_blank">PDF</a>, notes: <a href="./extra/Notes_on_PageRank.pdf" target="_blank">PDF</a>]|
<!--
| Lecture 20  | 05/16/2023 | Recommender Systems (Part II) | [slides: <a href="./slides/20_Recommender_Systems_(Part_II).pdf" target="_blank">PDF</a>]|
| Lecture 21  | 05/22/2023 | Recommender Systems (Part III) | [slides: <a href="./slides/21_Recommender_Systems_(Part_III).pdf" target="_blank">PDF</a>], notebook: <a href="./notebooks/MF_Recommender_Systems.ipynb" target="_blank">ipynb</a>]|
| Lecture 22  | 05/23/2023 | Graph Link Analysis | [slides: <a href="./slides/22_Graph_Link_Analysis.pdf" target="_blank">PDF</a>]|
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
