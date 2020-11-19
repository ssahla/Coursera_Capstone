# Helsinki Hoods
## Applied Data Science Capstone Project – The Battle of Neighborhoods
### Project Report
 
Simo Sahla


### 1. Introduction
If I were an entrepreneur planning to start a new restaurant in Helsinki, which neighbourhood would be a good choice for location? 

I would naturally want to choose a neighbourhood where there are lots of potential customers. On the other hand, I wouldn't want to pick an area that's already saturated with competing restaurants. In other words, I'd want to find a neighborhood with a low restaurants-to-citizens ratio.

In this project I'm trying to calculate this ratio for different Helsinki neighborhoods using FourSquare venue data and visualize it in a way that can give insights on business opportunities in different parts of Helsinki. I'm using restaurants as an example, but the same can be done for different types of venues.


### 2. Data
To achieve my goal I will be using the following data sources: 
- The FourSquare API will give me data for **numbers of venues** in different parts of Helsinki.
- The city of Helsinki has made available **geodata for neighborhoods of Helsinki**. With this I can plot the neighborhoods on the map as polygons.
- Also, **population numbers of each neighborhood** are available from the city of Helsinki and can be used to calculate the ratio of venues per capita.
