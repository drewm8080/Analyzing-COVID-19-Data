# Analyzing-COVID-19-Data
## **COVID-19DataSource**

Website: [covid19datasource.usc.edu](https://covid19datasource.usc.edu/)


In this repository, we go through three different data sources to create models to compare the data sources. The three different sources we use are:
1. [The New York Times](https://github.com/nytimes/covid-19-data)-- Reported cases and deaths
2. [Covid-19 Projections](https://covid19-projections.com/)-- Estimated cases and deaths
3. [Covidestim](https://covidestim.org/)-- Estimated cases and deaths
4. [Healthdata.gov](https://healthdata.gov/Hospital/COVID-19-Reported-Patient-Impact-and-Hospital-Capa/g62h-syeh)-- Reported Hospitalizations

# **How to use these files**
Simply run the whole code. The code will ask you for a state. Follow the direction given by the code and press enter. Scroll to the bottom and the statistics,table, and data visualizations will be generated.

# **Background to the models**
We used the Average Day of Case/Death/Hospitalization to compare the three sources goes as follows:

![image](https://user-images.githubusercontent.com/71193439/111383855-2e425600-867f-11eb-9f37-50e4063f4fb2.png)


Next, we looked at the ratios,difference of Average Day of Death/Hospitalization and Average Day of Case, and finally the CDFs of cases,deaths, and hospitalizations: 

![image](https://user-images.githubusercontent.com/71193439/111257178-102e1480-85f1-11eb-9ded-e60e726577a4.png)

![image](https://user-images.githubusercontent.com/71193439/111257219-1de39a00-85f1-11eb-974d-20db45c259cf.png)

![image](https://user-images.githubusercontent.com/71193439/111383044-1b7b5180-867e-11eb-8984-53624ed28e0e.png)

![image](https://user-images.githubusercontent.com/71193439/111257450-8b8fc600-85f1-11eb-92b0-da0193b7f8c3.png)

![image](https://user-images.githubusercontent.com/71193439/111383561-c7bd3800-867e-11eb-950a-2da65d60b4ca.png)

![image](https://user-images.githubusercontent.com/71193439/111257530-ad894880-85f1-11eb-9e23-c0f7858f00f4.png)

![image](https://user-images.githubusercontent.com/71193439/111257562-bed25500-85f1-11eb-910e-81fedb0bfc21.png)

![image](https://user-images.githubusercontent.com/71193439/111383284-609f8380-867e-11eb-95f0-c57f0602d593.png)

Through these metrics, we can compare states cases/deaths and get some insights:

1. Is the state reporting cases/deaths late?
2. How reliable is the data sources?
3. Is there discrepancies in the data?

We can compare the two estimated data sources (Covidestim and Covid-19 Projections) with the reported data (The New York Times) to get a better sense of the data. Finally, we plot the reported hospitalization data from healthdata.gov along with the curves of the estimated and reported data

# **Data Visualization Example**

Here is some example data visualizations for California from The New York Times and Healthdata.gov:

![image](https://user-images.githubusercontent.com/71193439/112216000-66a1e100-8bf7-11eb-8ed2-0bec91dd4aec.png)

![image](https://user-images.githubusercontent.com/71193439/112216016-6b669500-8bf7-11eb-9ce2-7d4585af70b0.png)

![image](https://user-images.githubusercontent.com/71193439/112216041-71f50c80-8bf7-11eb-9f54-2fc0dab0bd6b.png)

![image](https://user-images.githubusercontent.com/71193439/112216058-76b9c080-8bf7-11eb-9ae9-b8480f7e8a92.png)




