# Analyzing-COVID-19-Data
## **COVID-19DataSource**

Website: [covid19datasource.usc.edu](https://covid19datasource.usc.edu/)
NOTE: This is an on-going repository and is constantly being updated. 

In this repository, we go through three different data sources to create models to compare the data sources. The three different sources we use are:
1. [CDC Data](https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36)-- Reported cases and deaths
2. [Covid-19 Projections](https://covid19-projections.com/)-- Estimated cases and deaths
3. [Covidestim](https://covidestim.org/)-- Estimated cases and deaths

# **How to use these files**
Simply run the whole code. The code will ask you for a state. Follow the direction given by the code and press enter. Scroll to the bottom and the statistics,table, and data visualizations will be generated.

# **Background to the models**
We used the Average Day of Case and Death to compare the three sources goes as follows:

![image](https://user-images.githubusercontent.com/71193439/112330975-e6c75580-8c8e-11eb-85ad-3535f58b4449.png)


Next, we looked at the ratios,difference of Average Day of Death and Average Day of Case, and finally the CDFs of cases and deaths: 

![image](https://user-images.githubusercontent.com/71193439/111257178-102e1480-85f1-11eb-9ded-e60e726577a4.png)

![image](https://user-images.githubusercontent.com/71193439/111257219-1de39a00-85f1-11eb-974d-20db45c259cf.png)

![image](https://user-images.githubusercontent.com/71193439/111257450-8b8fc600-85f1-11eb-92b0-da0193b7f8c3.png)

![image](https://user-images.githubusercontent.com/71193439/111257530-ad894880-85f1-11eb-9e23-c0f7858f00f4.png)

![image](https://user-images.githubusercontent.com/71193439/111257562-bed25500-85f1-11eb-910e-81fedb0bfc21.png)

Through these metrics, we can compare states cases/deaths and get some insights:

1. Is the state reporting cases/deaths late?
2. How reliable are the data sources?
3. Is there discrepancies in the data?

We can compare the two estimated data sources (Covidestim and Covid-19 Projections) with the reported data (CDC Data) to get a better sense of the data.
# **Data Visualization Example**

Here is some example data visualizations from Covidestim for California:

![image](https://user-images.githubusercontent.com/71193439/112328552-d4e4b300-8c8c-11eb-910e-0ceda83c73bf.png)

![image](https://user-images.githubusercontent.com/71193439/112328574-d910d080-8c8c-11eb-8fc6-0f97f7b34c8a.png)

![image](https://user-images.githubusercontent.com/71193439/112328613-e332cf00-8c8c-11eb-8da0-807e22d9fa0e.png)






