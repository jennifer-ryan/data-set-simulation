# Dataset Simulation Project

This repository contains a dataset simulation as part of the assessment in the *Programming for Data Analysis* module for the Higher Diploma in Data Analytics with Galway-Mayo Institute of Technology.


## About this Repository

The repository can be accessed [here](https://github.com/jennifer-ryan/dataset-simulation). Clicking the 'clone or download' button will allow you to download the repository to your machine. Use the 'git clone' command followed by the repository link in your machine's command line to create a local copy for review. Some of the jupyter notebook output may not render correctly in the GitHub repository but should function as intended on a local machine. 

The contents of this repository are:

1. A **README** file that outlines the layout of the project.
2. A **Jupyter Notebook** that contains a detailed account of how the dataset was simulated. The notebook also contains a table of contents to aid navigation.


## Python Libraries

For this project I use the following Python libraries:

- **pandas** to create the dataframe and columns.
- **numpy** to populate the values in the dataset with randomised or conditional values.
- **scipy.stats** to access a truncated normal distribution.
- **matplotlib.pyplot** and **seaborn** for data and distribution visualisation.


## Project Requirements

- Choose a real-world phenomenon that can be measured and for which you could collect at least one-hundred data points across at least four different variables.
- Investigate the types of variables involved, their likely distributions, and their relationships with each other.
- Synthesise/simulate a data set as closely matching their properties as possible.
- Detail your research and implement the simulation in a Jupyter notebook


## Project Description

This project simulates a spreadsheet created by a woman who has tracked her weight loss efforts every day for a calendar year. It contains the following columns:

- **date:** a range of dates from 01/01/18-31/12/18.
- **day:** the day of the week for each date.
- **cals_in:** estimated total number of calories consumed each day.
- **tdee:** total daily energy expenditure estimate.
- **exercise:** exercise performed (walk, strength, yoga or none).
- **exercise_cals:** estimated calories burned by the particular exercise performed.
- **cals_out:** estimated total number of calories burned based on the sum of tdee and exercise_cals. 
- **cal_dif:** the difference between cals_in and cals_out.
- **gain_or_loss:** the weight loss or gain for the day based on the sum of cals_dif and a random positive of negative value. 
- **weight:** the weight recorded when stepping on the scale.
- **bmi:** body mass index.

Research was conducted on each variable to make them as closely representative of reality as possible. To avoid making the weight-loss results too predictive, values were randomly manipulated to account for realistic fluctuations. The dataset is built upon throughout the jupyter notebook and available in its entirety towards the end of the project. Some distribution plots and basic descriptive statistics are used to demonstrate the patterns created.