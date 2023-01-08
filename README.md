# Movie-Recomendation-Neural-Network
## Building a neural network that will predict a personal scores for movies

This is done by importing data via an excel spreadsheet with the properties of:
1. Title (The title of the movie)
2. Runtime (How long the movie is)
3. Genre
4. Sub-Genre
5. Personal score (a rating of of ten of how I liked the moive)

I then one-hot encode the data and normalize the data

I then split into my *inputs* and *labels* while having filters for the moives I have yet to have seen.

Next, the data is again split into training and testing data.

The neural network was then created using TensorFlow. 

I trained the network and then tested the network before giving the model the entire data set. 

The model then predicted the scores for all the moives including the ones that I yet to see. 

This data was then outputed to a excel file. 


