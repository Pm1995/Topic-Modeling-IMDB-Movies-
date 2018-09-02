# Topic-Modeling-IMDB-Movies-

## Overview
The project is intended for users who want to discover new movies they may not have seen yet. More specifically, it will help users find movies that are related to movies they have watched while also maintaining a similar rating. The project does topic analysis on the top and bottom 250 user rated movies on IMDb (a reliable source to find movie ratings) and generates multiple dynamic graphs. It is useful because it facilitates searching for a new movie by focusing on the visualization of the data, making it easier to analyze. 

## Methodology 
The probabilistic approach employs LDA to model user top and bottom IMDb rated movie summaries. We assume that movie summaries can be modeled as mixtures of topics, and that each topic represents a probability distribution over movies. In this process, it is expected to find the similarities in movies which are highly/lowly ranked.
