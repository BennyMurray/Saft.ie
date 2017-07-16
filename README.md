(Note: code for this repo is stored in a private repository to prevent misuse) 

# Saft.ie
A REST API providing live data and statistics on Ireland's rental and property markets


## Endpoints

**GET:** /all

**GET:** /rentals

**GET:** /purchasable

**Filters**

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
