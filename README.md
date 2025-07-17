# Semantic Data Integration

_Overview_

This project focuses on data integration across three datasets in the book domain: Amazon, Goodreads, and Kindle.

_Structure of the Project_

**Datasets** 
The datasets used in this project have been downloaded from Kaggle. Links to the datasets is as below;

**Dataset1_Amazon.xlsx **- TOP 100 BEST SELLING BOOKS ON AMAZON 2009-2021: https://www.kaggle.com/datasets/abdulhamidadavize/top-100-best-selling-books-on-amazon-20092021

**Dataset2_GoodReads.csv ** - Goodreads Choice Awards Best Books of 2023: http://kaggle.com/datasets/brzy56/goodreads-choice-awards-2023-best-books-of-2023

**Dataset3_Kindle.csv** - Amazon Kindle Books Dataset 2023: https://www.kaggle.com/datasets/asaniczka/amazon-kindle-books-dataset-2023-130k-books

**mediated_schema.csv** - Mediated schema file

_Implementation - This folder contains the Scripts and Datalog queries
_
**task.dl **- query scripts

**Matchers_Combiners.ipynb **- Implementation for Matching and Combining strategies

**Mediated_schema.ipynb** - Script to develop Mediated schema


_Reports_ - This folder contains Task Reports
**Report_Task_01:** Task 1 focused on integrating book-related data from Amazon, Goodreads, and Kindle. It involved collecting datasets, formulating competency questions, expressing them as conjunctive queries in Datalog, and designing a mediated schema. We also identified structural and semantic heterogeneity across the sources.
**Report_Task_02:** Task 2 involved implementing multiple matchers (Jaro-Winkler, SpaCy, and TF-IDF with Cosine Similarity), designing combiner strategies (Max and Weighted Average), and applying selection thresholds to identify best-matching entity pairs. Ground truth datasets were created to enable evaluation, and quality metrics such as precision, recall, and F1-score were computed to assess and compare the performance of different matcher-combiner combinations.

