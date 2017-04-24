# Project Question 

### What is the question you hope to answer?

RentHop is a web and mobile-based search engine that allows users to search for apartments in major metropolitan areas. I want to see if I can predict the number of inquiries a new listing receives on Renthop based on the listing’s creation date and other features.  Being able to predict the number of inquiries a listing will receive will allow owners and agents to better understand renters’ needs and preferences.

### What data are you planning to use to answer that question and what do you know about the data so far?

The data (https://www.kaggle.com/c/two-sigma-connect-rental-listing-inquiries/data) comes from a Kaggle competition and was collected from RentHop.com. The data set is large and consists of apartments listed in New York City.  The target variable,  “interest_level”, is defined by the number of inquiries a listing has in the duration that the listing was live on the site. The data fields are:

* bathrooms: number of bathrooms
* bedrooms: number of bathrooms
* building_id
* created
* description
* display_address
* features: a list of features about this apartment
* latitude
* listing_id
* longitude
* manager_id
* photos: a list of photo links. You are welcome to download the pictures yourselves from renthop's site, but they are the same as imgs.zip. 
* price: in USD
* street_address
* interest_level: this is the target variable. It has 3 categories: 'high', 'medium', 'low'

### Why did you choose this topic?

Moving to Seattle, as amazing as this city is, was a total pain when it came to finding a place to live.  I like the idea of improving search engines that will help people find a home in a large and possibly new city.
