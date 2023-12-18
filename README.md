
# Drug Seizure Analysis
<p align='center'> <img src='images/STOCK.jpg'></p>

## Overview
This Jupyter Notebook, international.ipynb, provides an analysis of international drug seizures and the US Opioid Seizured over time . It explores datasets related to drug seizures across different regions or countries, aiming to understand patterns, trends, and insights into this critical issue. It also provides a historical and political analysis of drug seizures made in the United States from 1980 to 2019. 

## Contents
**Introduction:**
This project was made to use a historical drug seizure data set in multiple ways. It was analyzed from world development indexes and from US history data points. This project was made to gain a more specific viewpoint on how drug seizure data can be explained by many different factors. 

**Project Hypothesis:**
1. Countries with a high CPI (Corruption Perceptions Index) will have more drug seizures throughout history. 
2. Countries with lower income classes will have a higher rate of drug seizures.
3. Republican Presidents will have more drug seizures than Democrat Presidents.

**Data Sources:** 

1. [Drug Seizures annually since 1970s](https://www.kaggle.com/datasets/ramjasmaurya/drug-seizues-annually-since-1970s)<br>
{Region, Country, ISO Code, Drug Group, Drug, Year, KG Equivalent}
2. [World Development Data](https://www.kaggle.com/datasets/keithvincentburca/world-development-data)<br>
{Country, electricity_access, gdp, gdp_capita, labor_rate, labor_force, land_area, life_expectancy, adult_literacy, water_access, air_pollution, population_density, population, alcohol_consumption, unemployment_rate, social_support, freedom, generosity, income_class, cpi}
3. US Presidents Data<br>
{President, Years in Office, Party}

**Data Cleaning and Preprocessing:**
The data was cleaned in various ways. The USO team by creating a new derivative dataset that only included the drug group opioid. The international team dealt with many missing values due to not every nation being reported in the drug seizure data set. All the nations that were not included were dropped by using the dropna method. 

**Exploratory Data Analysis (EDA):** 
The following images are exploratory data analysis from the project. 
<p align='center'> <img src='images/TOP10INCOME.PNG'></p>
<p align='center'> <img src='images/MEANSEIZUREINCOME.PNG'></p>
<p align='center'> <img src='images/INCOMESEIZURESLINE.PNG'></p>
<p align='center'> <img src='images/USOPIECHART.PNG'></p>
<p align='center'> <img src='images/USOBARGRAPH.PNG'></p>
<p align='center'> <img src='images/USODRUGSSEIZED.PNG'></p>


**Statistical Analysis:** Statistical analysis was performed on CPI vs Number of Drug Seizures for the Pearson's Correlation Coefficient. 

*Correlation Coefficient:*

Europe: 0.38 Low Correlation
<p align='center'> <img src='images/CPIEUROPE.PNG'></p>
Americas: 0.49 Moderate 
Correlation
<p align='center'> <img src='images/CPIAMERICAS.PNG'></p>
Africa: 0.25 Low Correlation
<p align='center'> <img src='images/CPIAFRICA.PNG'></p>
Asia: 0.41 Moderate Correlation
<p align='center'> <img src='images/CPIASIA.PNG'></p>
Oceania : 0.83 High Correlation
<p align='center'> <img src='images/CPIOCEANIA.PNG'></p>
All countries: 0.58 Moderate Correlation
<p align='center'> <img src='images/CPIDATA.PNG'></p>

**Results and Insights:** 
In the US, there has been a rise in the seizure of larger quantities of heroin over time, as evidenced by the summarized data. For the international part of the project, not all countries have historically reported seizures so that will affect the true nature of the data. 

**Conclusions:** 
1. Countries with a high CPI (Corruption Perceptions Index) will have more drug seizures throughout history. 

*There is a moderate positive correlation between CPI and historic number of drug seizures.*

2. Countries with lower income classes will have a higher rate of drug seizures.

*Lower middle income class has the highest rate of drug seizures.*

3. Republican Presidents will have more drug seizures than Democrat Presidents.

*Based on the data, republican presidents did not have more seizures than democrats*

### How to Use
This notebook is intended for individuals interested in understanding trends related to drug seizures on an international scale and from a US history perspective. To explore the analysis and findings:

Clone the Repository: Clone or download this repository to your local machine.
Jupyter Notebook: Open the international.ipynb and USO_Graphs.ipny file using Jupyter Notebook or JupyterLab.

Dependencies: Ensure you have all the necessary dependencies installed (Python, Jupyter, required libraries).

Required libraries: 

Matplotlib <br> 
pandas<br> 
scipy<br> 
Numpy<br> 
linregress <br> 
pprint<br> 
Geopandas<br> 
Requests <br> 

Execute the Notebook: Run each cell sequentially to replicate the analysis and view the results.


License :<br> 
MIT license 

Credits:<br>
Mari Zena, Michelle Minkowitz, Dara Adesina, Paola Roman

Disclaimer:<br>
The drug seizure dataset was found on kaggle, it is in no way verified information and this project is not intended for official use of any kind. 