# AFCON Analysis Over The Years

## Introduction
This Dataset is about  The Africa Cup of Nations (AFCON), which is the main international men's football championship of Africa organized by the Confederation of African Football (CAF).I Embarked on an exploration of the AFCON data to see through the rich tapestry of the tournament's history. Beyond the mere statistics lie untold narratives waiting to be unearthed, revealing the essence of what makes AFCON a cherished spectacle in the world of football. 
From tracking the evolution of goal-scoring trends to identifying the most dominant teams, each insight unveils another chapter of the tournament’s legacy, revealing its impact on players, fans, and the entire African continent.

## PowerBi Concept Applied;
  1. Power Query Editor
  2. Data Modelling: Stat Schema

## Problem Statement
1. How has the total number of goals scored in Afcon tournaments evolved over the years?
2. Which countries have produced the most top scorers?
3. Which players have the highest contribution to their team's goals in Afcon history?
4. Are there any trends or patterns in penalty goals across different Afcon Countries?
5. Which countries have the most win in Afcon history?
   
## Data Sourcing
This data from my data challenge group Datafrik on twitter. The dataset is in Excel workbook format, encompassing multiple sheets, each presenting distinct AFCON information: Goals By Year and Country, AFCON By Country, Top Goal Scorer, Number of Games, Number of Hatricks By Year, Number of Penalties By Year, AFCON’s Own Goal, etc.

## Data Cleaning/Transformation
I used power query editor in PowerBi for the cleaning and transformation, These are the steps taken;
1. I removed null values with Zero (0)
2. I made some of the tables first row the header
3. Then I unpivot the tables
4. Change data type From 'Text' to 'Whole Number'

## Data Modelling
PowerBi automatically connected some the related tables resulting in a star schema model. The AFCON Goals by Year and Countries is the fact table of the model,  AFCON By Country, Top Goal Scorer, Number of Games, Number of Hatricks By Year, Number of Penalties By Year, AFCON’s Own Goal are the dimenision table they are connected by the common colunn; Countries Column and Year/Edition column. I connected the remain two countries that where not connect; the AFCON by country and the AFCON podium finish.

## Data Analysis And Visualization

## Conclusion And Recommendation
