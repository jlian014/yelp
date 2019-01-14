Problem Statement: This tool will estimate the affluence of a neighborhood based on the number of $ of businesses and services (according to Yelp) in a given neighborhood. ($, $$, $$$) This tool will expect to get, as an input, a list of zip codes or names of neighborhoods and will estimate the wealth of the locality. While traditional methods typically estimate wealth of a locality based on demographic characteristics (e.g. income or unemployment rate), the novelty of this approach is in its use of big data related to commercial activity and cost of product and services as an indicator for affluency.


[yelp_IRS_postcode.csv](./Jane/yelp_IRS_zipcode.csv)

|Variables| dtype| description |
|-------|----|-----|
|postal_code|int64|zipcode|
|yelp_dollar_1|int|the number of businesses which have 1 dollar signs in this zipcode area|
|yelp_dollar_2|int|the number of businesses which have 2 dollar signs in this zipcode area|
|yelp_dollar_3|int|the number of businesses which have 3 dollar signs in this zipcode area|
|yelp_dollar_4|int|the number of businesses which have 4 dollar signs in this zipcode area|
|Total_Business|int|the totoal number of businsess in this zipcode area|
|STATE|object|States|
|income_level_1|float|the number of people whose income level lie in level_1 category(statistics from IRS)|
|income_level_2|float|the number of people whose income level lie in level_2 category(statistics from IRS)|
|income_level_3|float|the number of people whose income level lie in level_3 category(statistics from IRS)|
|income_level_4|float|the number of people whose income level lie in level_4 category(statistics from IRS)|
|income_level_5|float|the number of people whose income level lie in level_5 category(statistics from IRS)|
|income_level_6|float|the number of people whose income level lie in level_6 category(statistics from IRS)|


[yelp_zillow_neighborhood.csv](./Jane/yelp_zillow_neighborhood.csv)

|Variables| dtype| description |
|-------|----|-----|
|Neighborhood|object|Neighborhood names|
|city|object|city names|
|regionid|int|ID from Zillow reserach data to identify unique neighborhood|
|state|object|state|
|county|object|county|
|geometry|object|Polygon values for boundary of neighborhood, can be further used for mapping)
|yelp_dollar_1|int|the number of businesses which have 1 dollar signs in this zipcode area|
|yelp_dollar_2|int|the number of businesses which have 2 dollar signs in this zipcode area|
|yelp_dollar_3|int|the number of businesses which have 3 dollar signs in this zipcode area|
|yelp_dollar_4|int|the number of businesses which have 4 dollar signs in this zipcode area|
|Total_Business|int|the totoal number of businsess in this zipcode area|
|STATE|object|States|
|Rent|float|Rent per person in this neighborhood|