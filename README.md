# Coursera_Capstone


# Problem and Background
For this project I aim to explore and bring light into the culinaric possibilities in Cologne. It is a city which has a diverse offering of different Bars Restaurants and Cafes and it is nearly impossible to get to know all of them, not mentioning that there are closing and opening up new venues from time to time. As a person living in or visiting this city, there is so much to explore and a goal of this project is to help identifying those venues that are worth visiting without spending too much time researching the good spots. To achieve this I try to define a score for each venue depending on the price range, the distance from the current location and the rating. Derived from this score, I will recommend those venues in the closer area that "objectively" nice places. While this might not be helpful for users that are looking for specific categories like a cocktailbar or an italian restaurant, it is a helpful proposals for people that spend time in the are and want to discover new and lovely places that are worth to experience.

# Data
We use public libraries and API's in this project. We use Foursquare API, Some common Python Libraries for programming.

The available FourSquare location Data via the Foursquare API provide us with the necessary information to visualize the restaurants that are spread throughout the city. On a more detailed point of view, we can dive into specific neigbourhood or streets and find the best rated venues, the distance to the venue and the respective price category. All postal codes from the city of Cologne are available on "https://www.koeln.de/postleitzahlen" and the necessary location from the respective Cologne postal codes can be found on "http://www.fa-technik.adfc.de/code/opengeodb/PLZ.tab", which is a csv-file, similar to the Toronto example we had troughout the course.
With those data sources we can collect the information that we need to model the scoring system and recommend the places that scored the best.
