# LIRI-homework
## LIRI - A Node App via Command Line 

LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a Language Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.

## Usage

1. Clone repo
2. npm install
3. cd LIRI-homework
4. Please see `notes` below to run the app 
5. ENJOY! 

## Tech Used 

* NodeJS
* JavaScript
* NPM Request [Request](https://www.npmjs.com/package/request).
* NPM IMDB    [OMDB API](http://www.omdbapi.com).
* Ajax 

## License

N/A

##Notes 

* LIRI will display your latest tweets. If you dont have a Twitter account it will default to my Twitter if no parameters are inputted


Liri will work four different ways which can take in one of the following commands:

* `movie-this`

* `do-what-it-says`

##What Each Command Should Do

node liri.js movie-this `<movie name here>`
* This will output the following information to your terminal/bash window:
* Title of the movie.
* Year the movie came out.
* IMDB Rating of the movie.
* Country where the movie was produced.
* Language of the movie.
* Plot of the movie.
* Actors in the movie.
* Rotten Tomatoes Rating.
* Rotten Tomatoes URL.
* If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'
* If you haven't watched "Mr. Nobody," then you should: http://www.imdb.com/title/tt0485947/
* It's on Netflix!

node liri.js do-what-it-says
* This uses the fs Node package, LIRI will take the text inside of random.txt and then use it to call one of LIRI's commands.
