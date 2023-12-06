# How to Entertain a Juggler

A slide presentation by Jono

See it live here:

http://jonocodes.github.io/howToEntertainAJuggler/

## Use

There are two versions of the presentation.

index.html is the online version with references to youtube videos.

offline.html has local copies of the videos. This is because I was asked to give the presentation at an event with a questionable internet connection. (this version is likely less up to date)

## Credits

Slide framework provided by [reveal.js](http://lab.hakim.se/reveal-js/)

Youtube videos downloaded with [Tublet](http://www.saigonist.com/content/simple-download-youtube-html5)

Videos trimmed with ffmpeg:
ffmpeg -i 4count.webm -vcodec copy -acodec copy -ss 00:06:25 -t 00:00:21 4count_trimmed.webm
