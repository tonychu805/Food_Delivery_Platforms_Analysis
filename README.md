# US Food Delivery Platforms Analysis

Using a food delivery platform dataset in the US, I used R language to conduct data cleaning, feature engineering, and exploratory data analysis, while using Tableau to create an interactive dashboard to showcase actionable insights that the delivery analytics product team may take to maximize sales

## These are the columns of the ____ file contains:

restaurant_id       restaurant_id
name                name  
platform            platform
                    (Doordash, Postmates, Grubhub, Ubereats, Delivery.com, Caviar)
sub_platform        sub_platform
latitude            latitude
longitude           longitude
city                city
country             country
active              restaurant is currently delivering or not
                    (True, False)
standardized_name   standardized name to be processed
restaurant_chain    restaurant chain name
delivery_radius     delivery radius (in km)

Note the csv file uses ctrl-a as a delimiter

## Part 1: Data Cleaning 

Designed and implemented an algorithm using R code to reconcile and deduplicate the restaurant locations in the example dataset. Different physical locations of the same restaurant (for example, a McDonald's in Los Angeles vs a McDonald’s in New York) are identified as different restaurant locations

## Part 2: Analysis & Dashboarding

An exploratory data analysis to advise stakeholders on which area we should launch Otter. 
A Tableau dashboard is used to visualise the finding and filter by restaurant name and delivery platform.

Presentation slide may be found here: https://docs.google.com/presentation/d/1fcv7K0vxSrBWxyRH99rtU1w3BD2VbsgeYe6uky-mt-I/edit?usp=sharing
Tableau dashboard may be found here: https://public.tableau.com/app/profile/tony.chu3466/viz/OtterrestaurantanalysisV2/Dashboard1?publish=yes

# There are several questions about the Titanic data that I have:

# 1. Who was the oldest survivor and what does the distribution of passengers' ages look like?
# 2. Was there a relationship between age and survival rate?
# 3. Did having a cabin increase survival rate?
# 4. Did gender play a factor in terms of revenue and fare price?
