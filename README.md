# Big Data Computing

## News
- Online classes will also be recorded, so as to allow you to watch them offline at your own convenience.<br>
Video recordings will be compressed and uploaded to a shared Google Drive folder. I have already granted acces to that folder to all the students who are enrolled to our [Moodle web page](https://elearning.uniroma1.it/course/view.php?id=8460) _at the time I am writing_.<br>
**In case some of you haven't subscribed to Moodle yet, please do so as soon as you can!**<br>
Also, note that you **must** use your institutional credentials (i.e., ```@studenti.uniroma1.it```) to access the shared folder above.
- Due to the COVID-19 emergency, office hours are also suspended. Meanwhile, I will be reachable via email.
- On next week, classes will be streamed online via [Google Meet](https://gsuite.google.com/products/meet/) at the same time they were originally scheduled, i.e., **Tuesday** from **8:00AM** to **10:00AM** and **Wednesday** from **3:00PM** to **6:00PM**. To join the virtual room, please access the following URL on Tuesday a couple of minutes before the class starts using your institutional address: https://meet.google.com/pvs-cubs-gfw
- Following the restrictions imposed by the latest ordinance issued by the Italian government to contrast the COVID-19 emergency, _all_ classes are suspended **until Friday, April 3** as reported on the Sapienza's [website](https://www.uniroma1.it/en/notizia/online-classes-exams-and-graduation-sessions). 
- Due to unexpected issues, class lectures will start on **Tuesday, March 3** rather than February, 25 as originally scheduled. Apologies for the very short notice.

## General Information

Welcome to the Big Data Computing class!

This is a first-year, second-semester course of the [MSc in Computer Science of Sapienza University of Rome](https://www.studiareinformatica.uniroma1.it/master-course-computer-science).

This repository contains class material along with any useful information for the current academic year (2019/20).

### Class Schedule
- **Tuesday** from **8:00AM** to **10:00AM** (Room Alfa, via Salaria 113)
- **Wednesday** from **3:00PM** to **6:00PM** (Room Alfa, via Salaria 113)

### Office Hours
- **Tuesday** from **2:00PM** to **4:00PM**, Room G39 located at the 2nd floor of Building G in viale Regina Elena 295.

### Moodle Web Page
Students must subscribe to the Moodle web page using the same credentials (username/password) to access Wi-Fi network and Infostud services, at the following link: https://elearning.uniroma1.it/course/view.php?id=8460

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
- PySpark + Google Colaboratory

**Unsupervised Learning: Clustering**
- Similarity Measures
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
- Example: Click-Through Rate (CTR) Prediction (_to be confirmed_)

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

## Environment Setup
In this course, we will be using the Python application programming interface to the Apache Spark framework (a.k.a. [PySpark](https://spark.apache.org/docs/latest/api/python/index.html)), in combination with [Google Colaboratory](https://colab.research.google.com/) (or "Colab" for short). This will allows you to write and execute PySpark (as well as pure Python, for that matters) in your browser, with:
- Zero configuration required;
- Free access to Google's powerful cloud infrastructure (including GPUs);
- Easy sharing.

Of course, the same can be achieved also on your own local machine but that would require: _(i)_ dealing with clumsy installation issues that are very specific to your platform, and _(ii)_ sticking to "small" rather than real "big" data, as your machine cannot compare with Google's infrastructure!

Still, in case you would like to perform _also_ local mode installation, the following are the steps (along with some references) you need to take.

### Prerequisites:
- Install Python 3.6 (or later) via [Anaconda](https://www.anaconda.com/distribution/#download-section) along with Jupyter Notebook
- Install [Java 8](https://www.oracle.com/java/technologies/javase-downloads.html)
    - If your system has multiple JDK installations, use jenv to manage them (e.g., for macOS users, please refer to this [link](https://medium.com/@brunofrascino/working-with-multiple-java-versions-in-macos-9a9c4f15615a))
    - In your ```~/.profile```, ```~/.bash_profile```, or ```~/.bashrc```, let ```jenv``` for managing multiple JDKs by adding the following two lines: 
        - ```export PATH="$HOME/.jenv/bin:$PATH"```
        - ```eval "$(jenv init -)"```
    - Run ```jenv enable-plugin export``` to allow ```jenv``` to automatically set ```JAVA_HOME``` upon changes to Java local/shell/global versions
    - In your ```~/.profile```, ```~/.bash_profile```, or ```~/.bashrc```, set default ```JAVA_HOME``` (system-wide) as follows:
        - ```export JAVA_HOME=$(/usr/libexec/java_home -v $(jenv version-name))```

### Installation:
- Create a ```conda``` environment specifically for PySpark in combination with Python 3.6 (or later), and call it for instance "<code>PySpark</code>" (although you can choose any name you want):
    - ```conda create -n PySpark python=3.6```
    - Install required packages inside the newly created conda environment either via ```conda``` or via ```pip```:
        - ```conda activate PySpark```
        - ```conda install pip```
        - ```conda install numpy```
        - ```conda install scipy```
        - ```conda install pandas```
        - ```conda install scikit-learn```
        - ```conda install seaborn```
        - ```conda install ipykernel```
        - ```conda install findspark```
    - Install any additional packages:
        - ```conda install autopep8```
        - ```...```
        - ```conda deactivate PySpark```
    - Prepare a kernel for the newly created environment on Jupyter Notebook:
        - ```conda activate PySpark```
        - ```python -m ipykernel install --user --name PySpark --display-name "PySpark"```
        - ```conda deactivate PySpark```
    - Download from Apache the latest version of [Spark](https://spark.apache.org/downloads.html) (e.g., 2.4.5)
    - Untar the downloaded archive:
        - ```tar -xzf spark-2.4.5-bin-hadoop2.7.tgz```
    - Move the directory to a local folder (e.g., ```/opt/```, ```/opt/local/```, ```/usr/local/```, etc.) [might require sudo/administrator's password]:
        - ```mv spark-2.4.5-bin-hadoop2.7 /usr/local/spark-2.4.5```
    - Create a symlink so as to allow multiple versions of Spark:
        - ```ln -s /usr/local/spark-2.4.5 /usr/local/spark```
    - Update your ```~/.profile```, ```~/.bash_profile```, or ```~/.bashrc``` file as follows:
        - ```export SPARK_HOME=/usr/local/spark```
        - ```export PATH=$SPARK_HOME/bin:$PATH```
    - **NOTE: THIS STEP IS ONLY NEEDED IF YOU HAVE MULTIPLE JDK VERSIONS INSTALLED**
        - Go to ```/usr/local/spark/conf``` and create a ```spark-env.sh``` file (copying it from the template provided)
        - Enforce Spark to run on top of JDK 1.8 by copy-pasting the following into ```spark-env.sh```:
            - ```export JAVA_HOME=$(/usr/libexec/java_home -v 1.8)```

<hr>

## Class Material

| Lecture \# | Date | Topic                                         | Resource      | 
|------------|------|-----------------------------------------------|----------------|
| Lecture 1  | 03/03/2020 | Introduction to Big Data: Motivations and Challenges | [slides: <a href="./slides/01_Intro.pdf" target="_blank">PDF</a>] |
| Lecture 2  | 03/04/2020 | MapReduce Programming Model | [slides: <a href="./slides/02_MapReduce.pdf" target="_blank">PDF</a>] |
| Lecture 3  | 03/10/2020 | Apache Spark + PySpark Tutorial (I part) | [slides: <a href="./slides/03_Spark.pdf" target="_blank">PDF</a>, notebook: <a href="./notebooks/03_PySpark_Tutorial.ipynb" target="_blank">ipynb</a>] |
| Lecture 4  | 03/11/2020 | PySpark Tutorial (II part) + Clustering: Data Representation | [slides: <a href="./slides/04_Clustering.pdf" target="_blank">PDF</a>, notebook: <a href="./notebooks/04_The_Curse_Of_Dimensionality.ipynb" target="_blank">ipynb</a>] |
| Lecture 5  | 03/17/2020 | Clustering: Distance Measures | [slides: <a href="./slides/04_Clustering.pdf" target="_blank">PDF</a>] |
| Lecture 6  | 03/18/2020 | Clustering Algorithms: K-means | [slides: <a href="./slides/05_Clustering_Algorithms.pdf" target="_blank">PDF</a>] |
| Lecture 7  | 03/24/2020 | Document Clustering with PySpark | [slides: <a href="./slides/06_Document_Clustering.pdf" target="_blank">PDF</a>, notebook: <a href="./notebooks/07_Document_Clustering.ipynb" target="_blank">ipynb</a>] |
