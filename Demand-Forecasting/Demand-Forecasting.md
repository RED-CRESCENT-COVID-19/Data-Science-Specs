# Demand Forecasting
We therefore assume that two-thirds of cases are sufficiently symptomatic to self-isolate (if required by policy) within 1 day of symptom onset, and a
mean delay from onset of symptoms to hospitalisation of 5 days. 

[Data](https://www.imperial.ac.uk/media/imperial-college/medicine/sph/ide/gida-fellowships/Imperial-College-COVID19-NPI-modelling-16-03-2020.pdf) shows that upto 30% of those that are hospitalised will require critical care (invasive mechanical ventilation or ECMO) based on early reports from COVID-19 cases in the UK,
China and Italy (Professor Nicholas Hart, personal communication). Bed demand numbers assuming a total duration of stay in hospital of 8 days if critical care is not required and 16 days (with 10 days in ICU) if critical care is required. With 30% of hospitalised cases requiring critical care, we obtain an overall mean duration of hospitalisation of 10.4 days. 

## Objective

The present hospital and intensive care setup in Pakistan is wholy unprepared for this (Feel free to add numbers here. Reconfirming numbers from PRC).

The objective of the Demand Forecasting team is to combine data from the Symptoms, Seeding, and Location teams to determine the demand at:

1. PRC and Govt. Helplines
2. PRC Emergncy Camps and Govt Hospitals. 

NOTE: We will be recieving intake data from PRC Emergency Camps. Data from Govt Hospitals is subject to availiability.


## Methods

### SEIR as Baseline
The easiest way to model the dynamics of a disease is as a [SEIR (Suspected, Exposed, Infected and Recovered)](https://en.wikipedia.org/wiki/Compartmental_models_in_epidemiology#The_SEIR_model) compartmental epidemiological process.

This provides the baseline for the dynamics on top of a which traditional Demand Forecasting techniques can be applied. It is very important to note the non-linear/multiplicative dynamics of the underlying system before proceeding with any other analysis.

NOTE: The objective is not to develope complicated epidemological models, but to use the underlying dynamics while modeling demand. That said, if you have experience in epidemological modeling your insight would be really helpful.

### Demand Forecasting Techniques
Whatever works.

## Data Sources
1. Geo-Coded Symptom List from the 7K+ Volunteers in the field. [App Prototype](https://www.figma.com/proto/TtIl1Rei7WY6vMf7upypjA/Material-Design-Theme-Kit-Mine?node-id=22551%3A33034&scaling=scale-down)
2. Collected Data Sources from the other teams.


### Deliverables
1. Projections on Tehsil-wise cases
2. Forecast of Call Center Calls from each region
3. Forecast for arrivals at PRC Centers and Govt. Hospitals.

