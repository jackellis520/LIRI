# LIRI
A node app like SIRI

LIRI is a Language interpretation and Recognition Interface, and is interacted with through the command line to perform three commands.

As of now, LIRI can do these three things:

spotify-this-song: Will look up a specific song for you,
movie-this: Looks up a movie of your choice,
concert-this: Looks up an artist and tell you where and when their next live show is,
Using the spotify-this-song command, the user can look up a song of their choice. LIRI will respond with the artist, album and and a link to preview the song.

<img src="https://github.com/jackellis520/LIRI/blob/master/images/SuperstarrSpotify.PNG">

The movie-this command uses the OMDB API to query a movie search of the user's choice. It will respond with the title, the year of release, the runtime, and a link to an image of the poster.

<img src="https://github.com/jackellis520/LIRI/blob/master/images/300movie.PNG">

The concert-this command uses the BandsinTown API to search an artist of the user's choice. This search will return with the date and location of the selected artist's next live event.

<img src="https://github.com/jackellis520/LIRI/blob/master/images/ToolConcert.PNG">