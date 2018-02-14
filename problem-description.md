# Health Exploration and Analytics
## What makes us sick?

### General question
How does the environment we live in influence our health?

### 1. Gapminder data: demographics and economics (50 pts.)
Question: **How do economical factors influence health across countries?**
Gapminder collects data related to demographics and health in all countries. The focus of this problem is to see "the big picture" -- how health differs among countries and what possible factors can contribute to this (i.e. air quality, nutrition, spending on healthcare, crime, etc.). In this problem, we'll narrow down our scope to several factors.
Use the following datasets from Gapminder (http://www.gapminder.org/data/):
* life_expectancy_at_birth.xlsx
* under_five_mortality_rate.xlsx
* urban_population_pct.xlsx
* gdp_per_capita.xlsx
* agriculture_gdp_pct.xlsx, industry_gdp_pct.xlsx, services_gdp_pct.xlsx
* total_health_expenditure_gdp_pct.xlsx
* water_withdrawal_per_capita.xlsx
* coal_consumption_per_capita.xlsx
* carbon_dioxide_emissions_per_capita.xlsx
* electricity_consumption_per_capita.xlsx
* suicide_per_10k.xlsx

Each dataset is described well in the "About" worksheet. Note that there are a lot of missing data points.

The datasets in point 5 correspond to the three main economic sectors. You might combine them into one table (before you start work) if you wish.

Explore how all variables change by country and over time. Create plots as needed. Draw conclusions.

### 2. Gapminder data, part 2: Food and drink (20 pts.)
Let's refine our question: **How do our choices in food and drinks affect our overall health?**
Explore and analyze the following datasets. Draw conclusions. Try to integrate the data into what you already observed in the first part of the problem.
* food_consumption.xlsx
* sugar_consumption.xlsx
* alcohol_consumption.xlsx
* bmi_male.xlsx, bmi_female.xlsx, blood_pressure_male.xlsx, blood_pressure_female.xlsx, cholesterol_male.xlsx, cholesterol_female.xlsx

### 3. ATUS Health Data (30 pts.)
Question: **How do eating habits of US people influence their health?**
Now let's consider another survey, done in the US. The survey results are located [here](https://www.kaggle.com/bls/eating-health-module-dataset/data). The data description is a little hard to read at first, but it's really useful. We're mostly interested in the file named "ehresp_2014.csv". Feel free to add information from other files if you need.

The study contains information about the eating habits and general health of people in the US.

Tidy up, clean, explore and visualize the data. Draw conclusions. Compare your results to what you already found in the previous two problems.

### Guidelines
Start working with the datasets one by one. Clean them up and explore them as you go. Prepare several visualizations to help you understand what information is in the data. Always keep in mind the questions and don't go off on tangents too much.

It's better to show a little bit of work on every problem than do one problem entirely. The key point is that you must be able to integrate the newly-found evidence with what you already have.

The exam problems are big enough to guarantee several months of hard work :D. Don't push it too hard. You don't need to complete all tasks to get a grade. However, try to give it your best.

### Grading and requirements
You need to submit a Jupyter notebook (.ipynb file) and all other files (such as images, datasets, etc.) you have used for your analyis. You must work on at least one problem from the list described above. Your analysis should consist of at least 300 words, in English. You should make at least one conclusion.

You **are allowed** to ask for and post questions and partial solutions (no more than 30 lines of code) in the SoftUni forum. However, the entire project must be your own work.

You are **not required** to work on every problem to receive a grade.
You are **not required** to use Python but it's highly recommended.
You are **not required** to use any kind of modelling or machine learning.

Main grading points: **research and analysis quality**, **code quality**, usage of data, methodology (i.e. following the scientific method), project structure.

The maximum score is 100 points, with 20 bonus points (i.e. 120/100 is the maximum allowed score).