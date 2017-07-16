![saft 1 -01](https://user-images.githubusercontent.com/17185335/28251108-1a9fb7a4-6a6e-11e7-96b2-fa94b97ec8d3.png)

(Note: code for this repo is stored in a private repository to prevent misuse. It is not currently deployed). 

# Saft.ie
Saft.ie is a REST API that provides live data and statistics on Ireland's rental and property markets. Saft utilizes Python's multi-processing module and a headless browser to  anonymously, rapidly and politely scrape data. This data is then parsed using regex and beautiful soup, fed into a Django-managed database and serialized using Django Rest Framework. 


### Endpoints

**GET:** /all

**GET:** /rentals

**GET:** /purchasable



### Filters

price [int]

price_gte [int]

price_lte [int]

location [any province, county, town or village located in Ireland]

number_of_bedrooms [int] 

number_of_bedroom_gte [int] 

number_of_bedroom_lte [int] 

building_type [house, apartment, studio, flat]

first_listed_start [date]

first_listed_end [date]

property_views [int]

property_views_gte [int]

property_views_lte [int]

energy_rating [BER rating]
