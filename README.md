# US Food Delivery Platforms Analysis

Using a food delivery platform dataset in the US, I used R language to conduct data cleaning, feature engineering, and exploratory data analysis, while using Tableau to create an interactive dashboard to showcase actionable insights that the delivery analytics product team may take to maximize sales

## These are the columns of the "css_public_all_ofos_locations.csv" file contains:

- restaurant_id &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      restaurant ID <br/>
- name &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; name  <br/>
- platform &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; platform (Doordash, Postmates, Grubhub, Ubereats, Delivery.com, Caviar)  <br/>
- sub_platform &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; additional platform  <br/>
- latitude &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; latitude  <br/>
- longitude &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; longitude <br/>
- city &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; city  <br/>
- country &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; country <br/>
- active &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; restaurant is currently delivering or not (True, False) <br/>
- standardized_name &nbsp;   standardized name to be processed <br/>
- restaurant_chain &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; restaurant chain name <br/>
- delivery_radius &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; delivery radius (in km) <br/>

*** Note the csv file uses ctrl-a as a delimiter

## Part 1: Data Cleaning 

Designed and implemented an algorithm using R code to reconcile and deduplicate the restaurant locations in the example dataset. Different physical locations of the same restaurant (for example, a McDonald's in Los Angeles vs a McDonald’s in New York) are identified as different restaurant locations

## Part 2: Analysis & Dashboarding

An exploratory data analysis to advise stakeholders on which area we should launch Otter. 
A Tableau dashboard is used to visualise the finding and filter by restaurant name and delivery platform.

1. Presentation slide may be found here: https://shorturl.at/prsV4 <br/>
2. Tableau dashboard may be found here: https://shorturl.at/uSUV2

## Part 3: Three implications drawn from this analysis:

1. Franchise customers are often the ones that generate more revenue than SMB customers since they tend to purchase or implement systems by large across locations.
2. More Inactivities of delivery partner connections implies higher churns. 
3. To launch the Otter service among SMBs, we shall examine the cities with the highest restaurant concentrations (highest number of unique restaurants with active delivery partners), and thus cities with at least 5,000 unique restaurants were chosen for this analysis.
