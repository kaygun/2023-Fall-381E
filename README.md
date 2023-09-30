---
title: Introduction to Data Science 
subtitle: (Fall 2023, MAT381E)
author: Atabey Kaygun [(kaygun\@itu.edu.tr)](mailto:kaygun@itu.edu.tr)
date: Lectures Mondays 14:30-17:30 
geometry:
  - margin=20mm
hyperrefoptions:
  - linktoc=all
  - pdfwindowui
...

## Course Description

This hands-on course provides students with a practical introduction to data science, with a focus on data cleaning, feature engineering, and geographic data analysis using Python. Students will learn foundational concepts and techniques for importing, cleaning, transforming, visualizing, and extracting insights from complex datasets. 

The course begins with an overview of the data science workflow and an introduction to Python programming basics. Students will learn essential data cleaning skills such as handling missing values, detecting outliers, and transforming features. Through practical exercises using real-world datasets, students will understand various methods for exploratory data analysis and visualization using NumPy, Pandas, Matplotlib, Altair, and Vega.

A significant portion of the course covers feature engineering and selection techniques. Students will learn how to derive new features from existing data, select the most relevant features, and reduce dimensionality. The text processing unit covers important NLP techniques like cleaning text data, extracting keywords and summaries, creating text embeddings with models like Word2Vec and BERT, and topic modeling methods like LDA. These provide a good introduction to working with unstructured text data. The course also provides hands-on experience with geographic data analysis using Python. Students will work with geographic file formats and create informative maps, clusters, and heatmaps to reveal spatial patterns. 

Throughout the course, ethics in data science will be emphasized. Students will learn to critically evaluate the implications of data cleaning and feature selection on machine learning models. By the end of the course, students will have developed core practical skills for importing, wrangling, visualizing, and deriving insights from real-world data. Students will complete hands-on assignments and a final project focused on a dataset of their choosing.

## Technical Requirements

The course is an applied data analysis class.  This means the course requires a degree of proficiency of computational tools from which you are going to be responsible.

* [git](https://git-scm.com/) and [GitHub](https://github.com/)
* [Python](https://www.python.org) programming language (version 3.10 or higher)
* [Anaconda](https://www.anaconda.com/) or [Pip](https://pypi.org/project/pip/) package managers
* [Jupyter](https://jupyter.org/) notebook system
* [Markdown](https://en.wikipedia.org/wiki/Markdown) markup language

Installing and maintaining these systems on your machine is your responsibility. I can't help you if something doesn't work. You will need to figure it out on your own.  If you can't install these systems on your machine you may try to use an online service:

* [CoCalc](https://cocalc.com/) 
* [Google Colab](https://colab.research.google.com/)
* [Microsoft Azure Notebooks](https://visualstudio.microsoft.com/vs/features/notebooks-at-microsoft/)


## Course Management

I will make all of the course related announcement on İTÜ's course management system [NINOVA](https://ninova.itu.edu.tr). I will post the grades on NINOVA as well. So, do check it regularly.

### E-Mail Policy

I receive approximately 50 e-mails per day. So, if you need to contact me, use the subject ``MAT381E'' in your e-mails. Spend some time structuring your e-mail with grammatically correct sentences in Turkish or in English. Be polite, direct, and concise. State what you need in the first two sentences.  Sign your e-mails with your name and student number. If I can't figure out who you are and what you need within 30 seconds of opening your message, I will delete your e-mail with no response. You are hereby warned.

## Assessment

### Homeworks

Students will assessed through 4 small homework projects, of which the best 3 (each 15%) will be counted towards the final grade, and a final project over the course of the semester. The small projects need to be done for each student separately, while for the final project you may work alone or with a team no larger than 3 students. 

I am going to post the homework assignments on the [course github page](https://github.com/kaygun/2023-Fall-381E), you'll need to fill in the answers and post it on your own github account by the deadline. For the homeworks, you are going to need to open a [GitHub](https://github.com) account and create a **private** repository for this class.  I am going to pull your howeworks and final project from your GitHub repositories at 11:59PM of each deadline date. So, you must share your the repository with me at `atebey_kaygun@hotmail.com` by October 9th. If you do not follow these instructions, your homeworks will be regarded as *not submitted*.

| Assessment                 | Deadline |
|----------------------------|----------|
| **Github link**            | Oct 9    |
| Homework 1                 | Oct 23   |
| Homework 2                 | Nov 13   |
| **Final Project Proposal** | Nov 20   |
| Homework 3                 | Nov 27   |
| Homework 4                 | Dec 18   |
| **Final Project**          | Jan 8    |

There is no make-up for the homeworks. If you miss any of the homework deadline because of an emergency, do contact me to make an arrangement as soon as you can. If you miss any 2 of the homeworks, or if your total from homeworks is less than 35% you'll get a VF. If your final is less than 25%, or your total is less than 35% you'll receive an F. Note that the conditions for receiving a VF are both necessary and sufficient, while the conditions for receiving an F are only sufficient. This means you may still get an F with a higher score than 35% depending on the distribution of the scores.

### The Final Project

For the final project, you will need to write a detailed project proposal (minimum 2500 words) by the midterm that need to include

- The dataset(s) you are going to use with a detailed description
- The questions you would like to ask the dataset(s)
- The methods you are going to employ to answer the questions you ask 
- The list of team members, and division of labor (who will do what)

The proposal will count towards 15% of your final grade. The project itself covers the remaining 40%.

## Use of LLMs

This course will allow and even encourage students to leverage large language models such as ChatGPT and Claude during their learning process. However, students will be required to document their usage of these tools through logged transcripts. This will promote transparency and provide opportunities to reflect on how these powerful models should be appropriately leveraged. The goal is to amplify human learning while maintaining academic integrity.

## Course Outline

- Introduction to Data Science
- Python Programming Basics
- Data Formats
  - CSV, JSON, XML, XLSX
  - Working with different data formats in Python
- Data Sources and APIs
  - Web APIs
  - Open Data APIs (World Bank, Yahoo Finance, etc) 
  - Working with APIs in Python
  - Web scraping basics
- Data Cleaning, Preprocessing, and Transformation
  - Handling Missing Data
  - Detecting and Removing Outliers
  - Data Transformation
  - Data Formatting
  - Data Filtering
  - Dimensionality Reduction Techniques (PCA, LDA, etc)
- Exploratory Data Analysis and Visualization
  - NumPy for Numerical Data
  - Pandas for Data Frames
  - DuckDB for filtering data
  - Matplotlib for Plots and Charts
  - Altair and Vega for Interactive Visualizations
- Feature Engineering and Selection
  - Creating New Features from Existing Data
  - Transforming and Normalizing Features
  - Discretizing Continuous Features
  - Decomposing Features
  - Selecting Relevant Features
- Text Processing and Natural Language Processing
  - Working with Text Data
  - Cleaning and Normalizing Text
  - Keyword Extraction
  - Text Summarization
  - Text Embeddings (Word2Vec, GloVe, BERT)
  - Topic Modeling (LDA, LSI)
- Geographic Data Analysis and Visualization
  - Working with Geographic File Formats (Shapefile, GeoJSON, etc)
  - Geocoding and Reverse Geocoding
  - Spatial Joins
  - Creating Choropleth Maps
  - Heatmaps
  - Spatial Clustering and Point Pattern Analysis
  - Raster Analysis
- Ethics in Data Science


