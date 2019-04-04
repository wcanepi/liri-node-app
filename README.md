### Overview

## What is a LIRI? 

**LIRI**  is is a _Language_ Interpretation and Recognition Interface. **LIRI** is a command line node.js app that takes in parameters and gives you back data.

## What does this LIRI do? ##

**LIRI** allows you to search for events by artist/band, song details on Spotify, and movie details on OMDB.

**LIRI** uses the Node-Spotify API, the OMDb API and Axios.

### Search for song details on Spotify: ###

```
node liri.js spotify-this-song <TITILE OF SONG>
```

![Song 1](images/song1.png "Racks In The Middle")

![Song 2](images/song2.png "Walk This Way")

 

### Search for movie details on OMDB: ###

```
node liri.js movie-this <NAME OF MOVIE>
```

![MOVIE 1](images/movie1.png "The Notebook")
![MOVIE 2](images/movie2.png "Mr. Nobody")

### Execute commands in a file: ###

```
node liri.js do-what-it-says
```

![Do This](images/whatitsays.png "I Want It That Way")