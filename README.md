# NODE-LIRI-app

# Liri -- _Language_ Interpretation and Recognition Interface*

The user must enter 'node liri.js' into the command line followed by a command and then a search parameter.

There are four possible Commands: 'concert-this', 'spotify-this-song', 'movie-this', or 'do-what-it-says'


** spotify-this-song ** :notes: :musical_keyboard: :musical_score: :headphones:
The 'spotify-this-song' command uses the Spotify API to retrieve data about the song entered in the search parameter.

Example: 



** movie-this ** :video_camera: :camera: :tv: :vhs:
The 'movie-this' command uses the OMDb API to retreive data about the movie entered in the search parameter. The result will include the title, release year, IMDb rating, Rotten Tomatoes rating, country or countries it was filmed in, langauge(s), plot, and actors/actresses in the film.

Example:



** do-what-it-says ** :+1: :smile: :yum: :laughing:
The 'do-what-it-says' command reads the random.txt file and executes the parameters inside of it. By default it is set to 'spotify-this-song, I Want It That Way', but can be updated at another time. 

Example:



All results are returned in the command line, but also into a separate text file named 'log.txt' as well.

Technologies used: Javascript, Node.js, Moment.js, Spotify API, OMDb API
