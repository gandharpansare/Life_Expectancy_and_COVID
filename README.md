# **Life Expectancy and COVID: An Exploratory Data Analysis**

## **Overview**
This project explores the relationship between **GDP per capita and life expectancy** across **166 countries** spanning five continents from **2019 to 2021**. The objective is to analyze the impact of COVID-19 on life expectancy trends and to understand whether economic factors influenced these changes. Through **statistical modeling and data visualization**, this project presents key insights into the dynamics of life expectancy and economic development during the pandemic.

---

## **Research Questions**
- How are changes in life expectancy from 2019 to 2021 related to GDP per capita?
- How did life expectancy change from 2019 to 2021?
- How does the life expectancy change from 2019 to 2021 vary with GDP per capita in 2019? Can the trends be well-described by a
simple model such as a linear model, or is a more complicated model required?
- Do **regional variations** exist in these relationships?
- Can we fit an interpretable model (e.g. a linear model, perhaps with simple transformations) that explains the change
in life expectancy from 2019 to 2021?

---

## **Key Findings**
- **GDP and Life Expectancy (2021):** A strong **positive correlation** was observed, with **log-transformed GDP per capita** being a better predictor of life expectancy than raw values.
- **Life Expectancy Change (2019-2021):** Most continents saw a decline in life expectancy due to COVID-19, with **Oman experiencing the steepest drop (-5.46 years)** and **Oceania showing a slight increase**.
- **GDP and Life Expectancy Change:** No strong **linear** correlation was found, suggesting that **economic factors alone** do not explain changes in life expectancy.
- **Regional Variations:** The **Americas** experienced the **largest declines**, while **Oceania** remained relatively stable.
- **Statistical Modeling:** A **loess regression model** revealed a **non-linear** relationship between GDP per capita and life expectancy changes.

---

## **Dataset**
- countries.csv
- worldbank-gdp.csv
- worldbank-life.csv

---

## **Technologies Used**
- **Programming Language:** R
- **Data Visualization:** ggplot2, histograms, scatter plots, line graphs
- **Statistical Analysis:** Correlation coefficients, linear regression, LOESS modeling
- **Data Transformation:** Log-transformation of GDP per capita

---
## **Contributors**
Gandhar Ravindra Pansare

Gayatri Gattani

Rishikesh Kakde

Swarn Gaba

Feel free to reach out to the contributors for any questions 

