# Seeding Analytics

## Overview
Seeding Analytics means analyzing the spread of disease based on population movement. This is usally acheived using the first 2 steps of traditional [tranporation forecasting](https://en.wikipedia.org/wiki/Transportation_forecasting):

1. [Trip generation](https://en.wikipedia.org/wiki/Trip_generation) determines the frequency of origins or destinations of trips in each zone by trip purpose, as a function of land uses and household demographics, and other socio-economic factors.

2. [Trip distribution](https://en.wikipedia.org/wiki/Trip_distribution) matches origins with destinations, often using a gravity model function, equivalent to an entropy maximizing model.

## Data Collection
There is currently a dearth of Trip data available for large parts of Pakistan. One of the key tasks will be to curate datasets to calculate trip generation and trip distribution. This can be done by and not limited to the following methods:

1. Airplane Travel
2. Railway Tickets
3. Bus Tickets
4. Careem + Uber
5. Local Transport (Difficult)
6. Aggregate Satelite Imagery In Previous Years

## Deliverables
1. A basic model to calculate Transport Distribution
2. Thesil-wise Transport Distribution

Note: Done is better than perfect for this problem. Calculating aggregate transport flow will give us enough information to boostrap the analysis.
