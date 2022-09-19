# COVID_ANALYSIS USING SQL QUERIES
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

COVID DATA USED FOR THE ANALYSIS CAME FROM THE OPEN SOURCE WEBSITE LINK (https://ourworldindata.org/covid-deaths), THIS DATA IS FROM 1ST JAN 2020 TO 29TH AUG 2022. I HAVE SEPERATED THIS DATA INTO TWO DATASET ONE IS COVID_DEATHS DATASET AND ANOTHER IS COVID_VACCINATED DATASET (BOTH OF DATASETS ARE ATTACHED WITH COMMA SEPRATED VALUES EXTENSION) FOR 


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
aged_65_older                                       people over 65 years, 
median_age                                          median age, 
aged_70_older                                       people over 70 years, 
gdp_per_capita                                      gdp_per_capita of country
