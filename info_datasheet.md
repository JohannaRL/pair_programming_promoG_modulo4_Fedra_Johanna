## Información general sobre el datasheet 

 - Peliculas desde el 2008 hasta el 2021. 

Context:

There are six datasets movie_info dataset contains metadata and ratings of the movie and other regional datasets contains all box office collection region wise.

- Columnas_info:

movie_title -> The title of the movie.
release_date -> The release date of the movie
season -> Because the movies are from the United States, the seasons are based on the North American calendar.
phase -> The phase of the movie. Marvel phases are a way of grouping several films in the MCU together.
production_budget_in_million_(USD) -> The production budget of a movie.
worldwide_collection_in_million_(USD) -> World-wide collection of a film.
tomatometer -> Ratings or scores from Rotten Tomatoes Critics (Converted into decimal form)
tomato_audience_score -> Ratings or scores from Rotten Tomatoes Audience (Converted into decimal form)
imdb -> Ratings or scores from IMDB
metascore -> Ratings or scores from Metacritic Critics (Converted into decimal form)
meta_user_score -> Ratings or scores from Metacritic Users
#Country_names -> You will find this columns in other regional dataset which contains country names
Other_Countries -> This is a specific column in the dataset that states other countries that are not included because it is an added column to handle the missing data for the difference between worldwide collection and region-wise collection. There is also no official information about the box office of the other remaining countries


- Important Notes:

● Because the MCU began in 2008, it will not include any Marvel films that are not part of the MCU.
● Marvel TV series and animated series are not included.
● The dataset will be updated regularly once a new movie is released and their box office is published.
● Due to no official information about some countries' box office collections, there can be null values. There are many types to deal with and it may depend on your analysis.
● Another reason for null values is that some movies were never released in some countries, perhaps due to their censor board or may be due to pandemic.

- Data Extracted From:

• https://www.boxofficemojo.com/?ref_=bo_nb_hm_mojologo
• https://en.wikipedia.org/wiki/List_of_Marvel_Cinematic_Universe_films
• https://www.metacritic.com/
• https://www.imdb.com/
• https://www.rottentomatoes.com/