# Covid-19-HIV-AIDS
COVID-19 is a respiratory viral disease, the virus is transmitted through direct contact with respiratory droplets of an infected person and touching surfaces contaminated with the virus. The purpose of this analysis is to show the infection rate and mortality rate of the disease. <br />
While HIV, the virus that causes AIDS, is one of the world's most serious public health challenges but the world is committed to curbing new infections while ensuring that everyone with HIV has access to HIV treatment. <br />

# Background
Work on a Health/Disease Insight Analysis. You are to work on any two of the following diseases; Covid-19, Hepatitis, Malaria, Lassa fever, Cholera, or HIV/AIDs. You are to scrap, clean, and visualize data using Power BI and create a Disease and Infection Monitoring Dashboard. <br />

# Findings
Infected Demographic by Sex.<br />
Infected Demographic by age range.<br />
Reported cases by date.<br />
Affected locations heatmap.<br />
Mortality by type.<br />
Mortality by region.<br />
Mortality by sex.<br />
Mortality by age range.<br />
Mortality rate.<br />
Total death.<br />

# Data Sourcing and Cleaning
Both covid_19 and HIV/AIDS datasets was gotten from Kaggle.<br /> 
The datasets was cleaned and tranformed using excel and Power BI. <br />

## Covid_19 :
Caluation was done in the covid_19 dataset to get the total number of confirmed cases per month and also the total number of deaths cases, and the columns that are not needed were removed.(fig.1)

![covid](https://user-images.githubusercontent.com/109004397/201705707-fa5b8872-9f52-443f-9c82-602d608fb39d.png)  fig.1

## HIV/AIDS
The data was extracted from Excel and transformed using Power Query. (fig.2)

![HIV_table](https://user-images.githubusercontent.com/109004397/201713161-3b784644-90f7-4d16-b0e9-aa558d45d7af.png)  fig.2
<br />
<br />
<br />
And a data model was created which showed the relationships between the Fact and dimensions keys with tables as shown below. (fig.3)

![hiv_model](https://user-images.githubusercontent.com/109004397/201713226-01341043-57e3-4bea-b0e4-6dd5ff08c71f.png)  fig.3

# Insights
## Covid_19 insights :

![covid_fig 1](https://user-images.githubusercontent.com/109004397/201704278-6bf4ce5b-4bc0-45b6-af8d-fdbf8929bbf4.png)  fig.4

Europe has the highest number in regards to total Covid cases while Africa has the lowest. The United States of America has the highest total Covid cases amongst all the countries. (fig.4)
<br />
<br />
<br />
<br />
![covid_fig 2](https://user-images.githubusercontent.com/109004397/201704281-edfe5483-8e46-4f55-b38c-59cadeaa26bf.png)  fig.5

Region wise, Americans has the highest death rate in all region while Africa has the lowest. United States of America recorded the highest death rate according to the dataset presented. (fig.5)


## HIV/AIDS insights:

![hiv_fig 1](https://user-images.githubusercontent.com/109004397/201713338-d38e08fa-aa4a-4906-afe2-c93e6d34b952.png)  fig.6

Total Estimated number of people infected with HIV is about 16.56M while the estimated annual new HIV infection is about 3.37M. 40-49years age range seems to have the highest infection while 50-59years seems to have lower infection. Gender wise, it appears that more females are living with HIV than male. Country wise, we can see the top 10 countries with the highest infection, South Africa took the lead. Over the years, the rate of spread and the number of new reported cases had declined considerably. (fig.6)
<br />
<br />
<br />
<br />
![hiv_fig 2](https://user-images.githubusercontent.com/109004397/201713693-8fa82f7e-d7b7-471e-b82e-7fec8e02b60e.png)  fig.7

Total annual death is estimated at 486,000people from 1990 to 2020. Gender wise, the female gender has higher percentage of AIDS death than male while Eastern Africa has the highest number of death related to AIDS while Uganda has the highest death related to AIDS in Africa based on the dataset used. It also appears that age 40-49years recorded highest mortality rate while mortality rate is lowest between age 20-29years. (fig.7)
