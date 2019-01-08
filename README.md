# NODE-LIRI-app

# Liri -- _Language_ Interpretation and Recognition Interface*

The user must enter 'node liri.js' into the command line followed by a command and then a search parameter.

There are three possible Commands: *spotify-this-song*, *movie-this*, or *do-what-it-says*


**spotify-this-song** :notes: :musical_keyboard: :musical_score: :headphones:
The 'spotify-this-song' command uses the Spotify API to retrieve data about the song entered in the search parameter.

Example: 

![image](https://user-images.githubusercontent.com/42306913/50749430-10098180-11fc-11e9-8954-e54f20ac74b1.png)


**movie-this** :video_camera: :camera: :tv: :vhs:
The 'movie-this' command uses the OMDb API to retreive data about the movie entered in the search parameter. The result will include the title, release year, IMDb rating, Rotten Tomatoes rating, country or countries it was filmed in, langauge(s), plot, and actors/actresses in the film.

Example:

![image](https://user-images.githubusercontent.com/42306913/50749324-6e823000-11fb-11e9-8fd1-a6c8467f0ec7.png)


**do-what-it-says** :+1: :smile: :yum: :laughing:
The 'do-what-it-says' command reads the random.txt file and executes the parameters inside of it. By default it is set to 'spotify-this-song, I Want It That Way', but can be updated at another time. 

Example:

![image](https://user-images.githubusercontent.com/42306913/50751326-8f9c4e00-1206-11e9-8153-42bc2dd2e3ee.png)


All results are returned in the command line, but also into a separate text file named 'log.txt' as well.

check out this link for a visual display of the functioning app :octocat:
https://drive.google.com/file/d/1mIbRO7rFbPV-mcN3Erqo_MY4iZi2TF_1/view

**Note** you may have to download the video to view the app :grimacing:

Technologies used: Javascript, Node.js, Moment.js, Spotify API, OMDb API, NPM colors, DotEnv
