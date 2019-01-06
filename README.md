# NODE-LIRI-app

* Liri -- _Language_ Interpretation and Recognition Interface

The user must enter 'node liri.js' into the command line followed by a command and then a search parameter.

There are four possible Commands: 'concert-this', 'spotify-this-song', 'movie-this', or 'do-what-it-says'

'concert-this' :musical_keyboard:
The 'concert-this' command uses the bands in town API to retrive all upcoming concerts for an artist that is searched. Each venue, location and date is provided for all results. Moment.js is used to format the date from the Bandsintown API.

Example: 



'spotify-this-song'
The 'spotify-this-song' command uses the Spotify API to retrieve data about the song entered in the search parameter.

Example: 



'movie-this'
The 'movie-this' command uses the OMDb API to retreive data about the movie entered in the search parameter. The result will include the title, release year, IMDb rating, Rotten Tomatoes rating, country or countries it was filmed in, langauge(s), plot, and actors/actresses in the film.

Example:



'do-what-it-says'
The 'do-what-it-says' command reads the random.txt file and executes the parameters inside of it. By default it is set to 'spotify-this-song, I Want It That Way', but can be updated at another time. 

Example:



All results are returned in the command line, but also into a separate text file named 'log.txt' as well.

Technologies used: Javascript, Node.js, Moment.js, Bandsintown API, Spotify API, OMDb API
