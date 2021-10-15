# IntersectionalityInFilm
PIC16B Group Project - machine learning model that provides recommendations for films representing intersectional identities.

Abstract:

Diverse representation empowers viewers who share the same identity as the movie characters and the cast, as it reflects experiences that the viewers can sympathize with.

Accurate representation in media production includes not only having diverse set of cast shown on the big screen but also an equally heterogenous composure of the crew, cast production, and writers whose voices are echoed in the works we see.While the film and TV show industry have slowly included more variety in representations of identities in the starring roles, diverse representation is still sorely lacking and much of the representation that exists presently in the repertoire is far from being accurate.

Our model would allow users to input identities of interest and receive a list of best-rated film and TV shows reflecting those identities either through the story itself or the cast and the crew involved in its creation.






Planned Deliverables:

We are creating a webapp that will allow users to select from a certain criteria (input), such as Asian American, LGBTQ representation, etc., and receive a list of shows and films that are best-rated matches for that criteria (output). 

Full success: Full access for users to select the TV shows and movies that they would like to see based on the iMDB repository based on certain preferential characteristics of their choice. Basically, they select some parameters and get a list of recommendations as the output. They can choose what topics they would like and max length of film/episode 

Partial success: Code that showcases the pipeline needed to categorize TV shows and movies based on certain parameters that a user selects.

Interface: Web App




Resources Required:
We would be scraping our data from the Explore Keywords function on the IMDb website based on a list of keywords we have identified: https://www.imdb.com/search/keyword/

For instance, if a user selects "Asian American" as one of the criteria that they want to filter their movie results by, we will be scraping all 993 titles from this page with the keyword "Asian American" applied: https://www.imdb.com/search/keyword/?keywords=asian-american&ref_=fn_kw_kw_1



Tools and Skills Required:
Database management
Data wrangling
Web scraping
User input/selection
Ranking model: That selects best results based on certain parameters
 
Packages: sqlite3, pandas, scikit-learn

What We Will Learn:
While working on this project, we will learn how to manipulate and manage various sources of data so that we can match necessary conditions. In terms of project management, we will also learn how to manage our time, define our goals clearly, distribute work equally, and maintain transparency with each other. 

