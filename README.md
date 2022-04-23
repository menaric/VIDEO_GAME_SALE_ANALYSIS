# Video-Game-Sales-Analysis
This repository is a Mini Project for SC1015 Introduction to Data Science and Artificial Intelligence. <br>
It focuses on the analysis of the video game database from VGChartz. <br>

## Problem Statement
1. Predict the sale volume based on its attributes such as Developer, Publisher and Genre
2. Create a model to assist new / aspiring game developers in choosing desired attributes for their games, based on available data

## Collaborators
__Chee Wen Zhan__ : Data Scraping, Notebook Management <br>
__Bernard Chiang Zhi Heng__ : Linear Regression, Support Vector Regression <br>
__Tan Jia Ze__: Exploratory Data Analysis <br>

## Datasets
### vgsales.csv
This dataset is scraped on __27th March 2022__ from [VGChartz](https://www.vgchartz.com/gamedb/) site. <br>
This website displays details of various games, such as name, developer and sales. <br>
The Python program to scrape the website is created by github user _@hechmik_, which can be found [here](https://github.com/hechmik/vgchartzScrape). <br>
This program is a modified version of github user _@gregorut_'s program, which can be found [here](https://github.com/GregorUT/vgchartzScrape). <br>
Specifically, _@hechmik_'s program provides the option to turn off Genre scraping, which will save a lot of scraping time. <br>
For this project, Genre is not scraped, and instead will be imported from another dataset __vgsales_kaggle.csv__. <br>

### vgsales_kaggle.csv
The option to scrape the __Genre__ for the scraping program is turned off as it will greatly increase scraping time. <br>
Therefore, we will make use of another dataset scraped by github user _@gregorut_ who also scraped from the same VGChartz site. <br>
The dataset can be found [here](https://www.kaggle.com/datasets/gregorut/videogamesales). <br>
This dataset will only be used to import the Genres for as many game entries as possible. This dataset is not used for EDA and modelling. <br>
In this notebook, the dataset will have the filename __vgsales_kaggle.csv__. <br>

## Notebook

## Libraries and Models
- Pandas
- Seaborn
- Matplotlib
- Scikit-learn: Linear Regression, Support Vector Regression, GridSearch

## References
- https://www.vgchartz.com/gamedb/
- https://github.com/hechmik/vgchartzScrape
- https://github.com/GregorUT/vgchartzScrape
- https://www.kaggle.com/datasets/gregorut/videogamesales
- https://www.nintendo.com/about/
