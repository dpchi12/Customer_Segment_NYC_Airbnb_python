# Customer Segmentation on New York City AirBnB Data
## Business Problem
With hundreds of thousands of listings available on the Airbnb platform across various locations, it is essential to understand customer preferences and segment them effectively. This is crucial for both hosts and Airbnb to maximize occupancy rates, set optimal pricing, and offer personalized experiences.

In this project, our team will analyze Airbnb listings in New York City to optimize Airbnb's offerings and pricing strategies. By categorizing the listings based on price and room type, Airbnb can enhance its recommendation algorithms to better align with customer preferences.


Later on, classification algorithms will be applied based on these variables:

**Target Variable: Customers segment (by price per room type) <br>
Feature Variable: minimum nights, neighborhood group, hosts' listings count, number of reviews and the availability of the listing**
## Attribute Information:

This dataset contains 48,895 rows and 16 columns.

1. ID: A unique identifier for each listing.
2. Name: The name of the Airbnb listing.
3. Host_id: A unique identifier for each host.
4. Host_name: The name of the host.
5. Neighbourhood_group: The larger area or borough where the property is located (e.g., Manhattan, Brooklyn).
6. Latitude: The latitude coordinate of the property’s location.
7. Longitude: The longitude coordinate of the property’s location.
8. Room_type: The type of room offered, e.g., Entire home/apt, Private room, Shared room. <br>
  *   Entire apartment - Studio apartment; a single apartment unit for yourself.
  *   Private room - Shared room in an apartment.
  *   Shared room - Dormitory situation.
9. Price: The nightly price of the listing in USD.
10. Minimum_nights: The minimum number of nights a guest must book.
11. Calculated_host_listings_count: The total number of listings managed by a host.
12. Availability_365: The number of days in a year the property is available for booking.
13. Number_of_reviews: Total number of reviews received by the listing.
14. Last_review: The date of the most recent review for the property.
15. Reviews_per_month: The average number of reviews the property receives per month.

## Require libraries for our project
pandas

numpy

matplotlib

seaborn

geopandas

mapclassify

wordcloud

pillow

sqlite3

scikit-learn


The data set can be found in the [Data](https://github.com/dpchi12/Customer_Segment_NYC_Airbnb_python/tree/main/Data) folder, and all notebooks related to our work can be found in [Notebooks](https://github.com/dpchi12/Customer_Segment_NYC_Airbnb_python/tree/main/Notebooks). 
Besides, during the Explordinarory Data Analysis, we created an [interactive map of Airbnb in New York City](https://dpchi12.github.io/Customer_Segment_NYC_Airbnb_python/airbnb_nyc_interactive_map.html) that displays all the listings with prices above 2000. By looking at the map, we can further support our hypothesis that the majority of the most expensive listings are in Manhattan. There are also quite a few of those in Brooklyn but nevertheless, it is obvious which area has the most prestigious apartments. 

