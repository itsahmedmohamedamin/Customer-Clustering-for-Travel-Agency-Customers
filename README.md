# Customer-Clustering-for-Travel-Agency-Customers

## Enclosed is a comprehensive data analysis for a travel agency, accompanied by an unsupervised machine learning model that identifies customer clusters and behavioral patterns within the agency's clientele.

1- **Heatmap of Corellation Matrix**

![download (1)](https://github.com/itsahmedmohamedamin/Customer-Clustering-for-Travel-Agency-Customers/assets/50253297/0459554f-ce03-493c-b205-478406c99ad5)

> The heatmap of the correlation matrix reveals several notable correlations within the dataset. A strong positive correlation is observed between site_name and hotel_country, indicating a potential relationship where specific sites may correspond to particular countries. Similarly, orig_destination_distance shows a substantial correlation with both hotel_country and hotel_continent, suggesting that the geographical distance is likely related to the location specifics of hotels.

> Additionally, hotel_country and hotel_continent exhibit a strong mutual correlation, which is intuitive, as hotels within a given country are inherently located on the same continent. This relationship is bidirectional and signifies redundancy between these two features.
> 
> There is also a discernible correlation between hotel_continent and hotel_market, as well as between orig_destination_distance and hotel_market, which may imply that certain markets within continents are more prevalent destinations, and the distance to these markets could be a significant factor for consideration.

2- **Plotting Some Data**

![download](https://github.com/itsahmedmohamedamin/Customer-Clustering-for-Travel-Agency-Customers/assets/50253297/e801517e-2fd3-4361-aee4-af87c9f4be44)


> The predominant channel utilized by customers is channel 10.

> A significant majority of transactions do not result in immediate bookings.

> Desktop platforms are preferred over mobile for these transactions.

> Additionally, the data indicates that the majority of customers do not specify the original destination distance.

> Room searches are typically for a single room, with most bookings comprising two adults and no children.

3- **Visualizing Number of Attempts per user**

![download](https://github.com/itsahmedmohamedamin/Customer-Clustering-for-Travel-Agency-Customers/assets/50253297/960ee7de-1195-490d-a81d-8cd4ce8355c8)

> The histogram indicates that the vast majority of users have only made one booking attempt, as shown by the high frequency for the count of 1. There is a significant drop in frequency for two attempts and it decreases even further for three or more attempts. This suggests that most users either book on their first attempt or do not make additional attempts.

4- **Distribution of User Continent**

![download](https://github.com/itsahmedmohamedamin/Customer-Clustering-for-Travel-Agency-Customers/assets/50253297/852980b9-bc88-4e12-acef-0280438dbdd8)


> The majority of users appear to initiate three booking attempts, indicating a robust level of repeat engagement with the agency's services.

5- **Trend of Bookings Over Time**

![download](https://github.com/itsahmedmohamedamin/Customer-Clustering-for-Travel-Agency-Customers/assets/50253297/e0cd3d2b-caad-4b7e-8f23-1d6013584ef8)


> The graph indicates a marked decline in booking activity from August through November 2013, after which bookings return to higher levels, albeit with several notable downward fluctuations.

6- **Original Destination Distance by Booking Status**

![download](https://github.com/itsahmedmohamedamin/Customer-Clustering-for-Travel-Agency-Customers/assets/50253297/094dc8a7-c5e1-467b-ae46-292ef4a29829)

> The majority of individuals do not make bookings at the most frequently searched destinations.

7- **Number of Room Count by Hotel Continent**

![download](https://github.com/itsahmedmohamedamin/Customer-Clustering-for-Travel-Agency-Customers/assets/50253297/21b7319a-efa9-4d9a-a6f4-c6a7831f65f7)

> The average Room Count is almost the same in different Hotel Continents


8- **Search Duration Distribution**

![download](https://github.com/itsahmedmohamedamin/Customer-Clustering-for-Travel-Agency-Customers/assets/50253297/75ed7475-e9ad-438f-b033-120f2ccc1d5f)

> Most Search Durations is between 0 and 15 and it mostly tends to 0


9- **Days in Advance vs. Duration**

![download](https://github.com/itsahmedmohamedamin/Customer-Clustering-for-Travel-Agency-Customers/assets/50253297/21c2b3cd-2603-41be-9da8-14cf9e41d776)

> The majority of customers have a duration ranging from 0 to 40 days, with a minimal number of customers experiencing durations exceeding 50 days.


## Now, Let's Analyze the clusters from the Unsupervised ML model

1- **The analysis of the dataset revealed the presence of six distinct clusters, each representing unique behavioral patterns among the users.**

![download (12)](https://github.com/itsahmedmohamedamin/Customer-Clustering-for-Travel-Agency-Customers/assets/50253297/4d421e18-5130-4811-b7f9-cff7993e4b32)

2- **As depicted in the graph below, Cluster 2 exhibits the highest count.**

![download (13)](https://github.com/itsahmedmohamedamin/Customer-Clustering-for-Travel-Agency-Customers/assets/50253297/652d7e5c-a9f8-48b0-9fb6-997c86c94416)
