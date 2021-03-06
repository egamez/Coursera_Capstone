## The Problem

The problem is the following: _I want to explore, all the available choices in the city, to find some commercial places, all close to each other_

Finding certain venues near a specific one it is not always a straighforward task, even worse, finding more than one choice for those kind of combinations in the same city may take you more time than the one that you are willing to spare doing so. Many specialized websites offer search engines but they seek only for similar places or acording some commercial relations.

The problem I want to solve it is to find different types of venues, all close to each other (in the same city), find all the possible combinations (of these vanues in different locations, or clusters) and provide some score about how many of this venues we found and how close to each other they are, i.e. find a hotel near to a jazz club and all of them near to budist temple, all of them in the same city, and if there are many choices, rate all the choices to take the better choice.

This solution can be used for independent business which want to add an extra to the services or products that already offer, travel agencies to promote extra activities, hotels to include extra, entrepeneurs who seeks new locations around potential clients, travellers who want to make some specific schedules, etc.


## The data

The proposed solution will make use of the [Foursquare location data](https://developer.foursquare.com/places) to find the venues and their geographical location.

The [Foursquare Places](https://developer.foursquare.com/places) service provides us, throught its API, a tool for location discovery
> 62M+ Global Venues, 190+ Countries and 50 Territories, 900+ Venue Categories, and, 30+ Attribute Fields (Foursquare developers, 2020)

The data retrieved comes with geographical coordinates for each venue retrieved, and can be filtered by categories.

It is with these information, that we seek for geographical clusters of all the venues and report a score according how close and how many venues are on each cluster found.


## References
Foursquare developers. (2020). _Foursquare Developer_. Retrieved from: https://developer.foursquare.com/places
