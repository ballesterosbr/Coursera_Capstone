# Capstone Project - The Battle of the Neighborhoods (Week 2)

### Applied Data Science Capstone by IBM/Coursera

## Table of contents
* [Introduction](#introduction)
* [Data](#data)
* [Methodology](#methodology)
* [Results and conclusions](#results-and-conclusions)

---

## Introduction
The main goal of this project is to define where the best place is in Vancouver (Canada) to open a new restaurant specialized in Mediterranean cuisine. In order to answer this question, we will analyze the venues of Vancouver and get all the information about the restaurants that currently exist in Vancouver. To approach the project, we will use the Foursquare API, which will help us in collecting the information such as tips, restaurant's category and more. This will let us to know which is the most common category of restaurants, so we will know if there are more popular restaurants than others. Finally, we will know if it is viable to open the restaurant or not depending on the analysis. The most important task is to detect potential competitors.

**Main goal**

Search for business opportunities starting with the opening of a new Mediterranean cuisine restaurant in Vancouver.

**Target Audience**

The following target populations would be potential clients: students, tourists, workers, families.

---

## Data

Based on definition of our problem, factors that will influence our decision are:
* number of existing restaurants in the neighborhood (any type of restaurant)
* type of restaurants in the neighborhood

Following data sources will be needed to extract/generate the required information:
* Number of restaurants and their type and location in every neighborhood will be obtained using **Foursquare API**.
* Coordinate of different locations in Vancouver will be obtained using **Nominatim Software**.
* Vancouver postal codes from Wikipedia: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_T (only those from "Vancouver").

---

## Methodology

In order to solve this problem, a lot of descriptive analysis have been done. Knowing that the goal is to identify the friendliest region for a Mediterranean restaurant, many tables have been created with information such as the number of foreign restaurants per neighborhood, bar graphs and histograms to study its distribution and frequency. The analysis was only focused in Vancouver city, so a lot of neighborhoods were discarded to improve the results of our exploratory analysis, which means that those are not good places to open a Mediterranean restaurants). Taking into account that this problem requires descriptive analysis and exploratory data analysis, machine learning techniques weren't needed because the exploratory analysis was enough to solve the classification problem.

---

## Results and conclusions

The purpose of the analysis was to identify Vancouver areas close with mid number of restaurants in order to search an optimal location for a new Mediterranean restaurant.

By calculating restaurant density distribution from Foursquare data we have first identified neighborhoods without potential competitors that justify further analysis. Then generated collection of locations which satisfy some basic requirements regarding existing nearby restaurants. We located the restaurants in the areas with more possibilities based on: competetitors, number of restaurants and type of restaurant.

Based on the analysis we have four potential locations to open a new Mediterranean restaurant.

- East Fairview, South Cambie
- North Grandview-Woodland
- SE West End, Davie Village
- Waterfront, Coal Harbour, Canada Place

The first three neighborhoods have a very good chance of being a success zone for our restaurant. This is because restaurants in that areas specialize in Asian cuisine. Thus, we can look for other types of potential clients in the area.

In the last area, the most common restaurants tend to be more varied than in the previous areas. It is a good area, like *SE West End, Davie Village* because it is close to the airport and can be a good location to attract clients such as tourists.

Final decission on optimal restaurant location will be made by stakeholders based on specific characteristics of neighborhoods and locations in every recommended zone, taking into consideration additional factors like attractiveness of each location (proximity to park or water), airport, schools, universities, proximity to major roads, real estate availability, prices, social and economic dynamics of every neighborhood etc.
