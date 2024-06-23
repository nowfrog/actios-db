# actios-db
A simple movie watchlist made with iOS Shortcuts.

## How does it work?
The shortcut works by creating .json files containing movies info taken from themoviedb.org. Their APIs are free for small projects, so you can easily put in the shortcut your API key and use it freely. 
Moreover, there is a simple function to import movies from a iMDB list, even though the .csv still needs to be optimized by hand (I am working on improving the import process). 
There is a second shortcut, "add to actios", that allows for movies to be added to the lists thanks to the aforementioned APIs. To add a movie to a list, simply share the corresponding iMDb page of the movie back to actios through the "add the actios" shortcut. Youcan search for a specific movie directly through actios, thanks to the search function (externally and internally).

Ideally, the shortcut can potentially be linked with a web interface to view the lists on any device. An example of this can be seen here: https://nowfrogmovielists.000webhostapp.com/

## Disclaimer
This is really alpha stage, so you will need to tinker a bit with it in order to set it up on your device. I am working to improve the shortcut in order to adapt it for the general public.

## Installation guide
Install both shortcuts ("actios-db" and "add to actios") and add your tmdb API key to the second one (simply edit the shortcut and paste it in the first link block.
In case of errors, they're probably linked to the relative path of files (thanks iOS!). I am working on fixing this kind of errors in the next update, but in the meantime you could change them yourself.
