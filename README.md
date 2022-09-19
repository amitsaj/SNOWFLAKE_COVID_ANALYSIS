# COVID_ANALYSIS USING SQL QUERIES
![](Screenshot%20(12).png)
---------------------------------
DESCRIPTION

Coronaviruses are a family of viruses that can cause respiratory illness in humans. They are called “corona” because of crown-like spikes on the surface of the virus. Severe acute respiratory syndrome (SARS), Middle East respiratory syndrome (MERS) and the common cold are examples of coronaviruses that cause illness in humans.
The new strain of coronavirus — SARS-CoV-2 — was first reported in Wuhan, China in December 2019. It has since spread to every country around the world.
COVID-19 symptoms vary from person to person. In fact, some infected people don’t develop any symptoms (asymptomatic). In general, people with COVID-19 report some of the following symptoms:
Fever or chills.
Cough.
Shortness of breath or difficulty breathing.
Tiredness.
Muscle or body aches.
Headaches.
New loss of taste or smell.
Sore throat.
Congestion or runny nose.
Nausea or vomiting.
Diarrhea.
Additional symptoms are possible.

OBJECTIVE:
To analyse and create reports for the covid situation worldwide along with india's covid report. exploratory analysis are being done having major foucus areas like covid deaths, cases, vaccinations, booster jibes, death percentage, cases percentage, top vaccination nations.

DATASET DESCRIPTION:

COVID DATA USED FOR THE ANALYSIS CAME FROM THE OPEN SOURCE WEBSITE (https://ourworldindata.org/covid-deaths), THIS DATA IS FROM 1ST JAN 2020 TO 29TH AUG 2022. I HAVE SEPERATED THIS DATA INTO TWO DATASET ONE IS COVID_DEATHS DATASET AND ANOTHER COVID_VACCINATED DATASET (BOTH OF DATASETS ARE ATTACHED WITH COMMA SEPRATED VALUES EXTENSION) FOR DOING SPECIFIC ANALYSIS ON DESIRED FIELDS ONLY AS THIS DATASET CONTAINS A LOT OF PARAMETERS/FIELDS WHICH CAN DIVERGE THE DESIRED ANALYSIS. 


FIELDS                                                    DISC

iso_code                                           country name abbrevation, 
continent                                           name of the continent, 
location                                            full country name, 
`date`                                              date, 
total_cases                                         no of total cases, 
new_cases                                           no of new cases, 
total_deaths                                        no of total deaths, 
new_deaths                                          no of new death, 
population                                          total population of the country, 
icu_patients                                        no of icu_patients, 
hosp_patients                                       no of hospitalize patients, 
weekly_icu_admissions                               no of weekly_icu_admissions, 
weekly_hosp_admissions                              no of weekly_hospitalized_admissions, 
new_tests                                           no of tests, 
positive_rate                                       covid positive rate, 
total_vaccinations                                  total_vaccinations, 
people_vaccinated                                   no of people vacinated, 
people_fully_vaccinated                             fully vaccinated people, 
total_boosters                                      total boosters jibes, 
new_vaccinations                                    new vaccinations, 
aged_65_older                                       avg people over 65 years, 
median_age                                          median age, 
aged_70_older                                       avg people over 70 years, 
gdp_per_capita                                      gdp_per_capita of country

TOOLS/SOFTWARE USES FOR ANALYSIS:
* SNOWFLAKE:
Snowflake is a cloud computing–based data cloud service. It was founded in July 2012 and was publicly launched in October 2014 
it is a cloud-based data storage and analytics service, generally termed "data-as-a-service". It allows corporate users to store and analyze data using cloud-based hardware and software.

* POWER BI:
Power BI is an interactive data visualization software product developed by Microsoft with a primary focus on business intelligence. It is part of the Microsoft Power Platform. Power BI is a collection of software services, apps, and connectors that work together to turn unrelated sources of data into coherent, visually immersive, and interactive insights. Data may be input by reading directly from a database, webpage, or structured files such as spreadsheets, CSV, XML, and JSON.

ANALYSIS TASKS:

* using sql query in snowflake find percentage of death and covid cases in india, percentage of covid cases and deaths worlwide, total death count and cases count, leading covid cases country worldwide, leading covid death coutryworldwide, top 10 vaccinated countries and top 10 booster jibe providing coutries etc

* After using all these sql queries and importing the queries to POWER BI, I created bar chart, line chart, column chart, filled map, table chart for the given query
using power bi and further creating power bi reports for my analysis.


CONCLUSION
* After completing analysis it is clearly visible that north america is leading covid death cases and leading covid cases continent worldwide with in which united state of america is leading covid death and cases country. while asia is at the second position.
* India is the second highest covid cases country in the world while 3rd highest in covid death cases while brazil is second highest covid death cases country in the world.
* top 3 vaccination providers are 
1 = china 
2 = india
3 = USA
* top 3 booster jibe providers are
1 = china
2 = india
3 = USA
* highest hospitalize patients and icu patients are from Europe and North america respectively.
* highest covid cases for a single month is on january 2022 which is around 380 million cases while maximum covid death on a single month occured on jan 2021.
* maximum covid death and covid cases in india occure in year 2021 which are 325k and 24.6 million respectively.
* 



