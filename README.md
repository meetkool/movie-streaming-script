Movie Streaming Script
======================

This script allows users to stream movies and TV series from a web browser using IMDB or TMDB ID's. The script is written in PHP and uses The Open Movie Database (OMDb) API to fetch movie and TV series details and streams the movie/series using the VideoJS library.

Installation
------------

To use this script, you'll need to have a web server running PHP and a web browser that supports HTML5.

1.  Clone the repository by running the following command in your command prompt:

Copy code

`git clone https://github.com/username/movie-streaming-script.git`

2.  Copy the files to your web server's document root directory.
    
3.  Make sure that the web server has the permissions to read the movie files.
    
4.  Download and copy the VideoJS library from ([http://videojs.com/](http://videojs.com/)) in your local folder
    
5.  In the movie-streaming-script folder, you will find a "se\_player.php" file, open it and change the path to point to your videojs folder.

Usage
-----

1.  Open a web browser and navigate to the URL of the script on your web server (e.g. [http://your-server/movie-streaming-script/se\_player.php](http://your-server/movie-streaming-script/se_player.php))
    
2.  You can request for a movie by its IMDB ID by using this format: `https://yourwebsite.com/se_player.php?video_id=tt8385148`
    
3.  You can request for a movie by its TMDB ID by using this format: `https://yourwebsite.com/se_player.php?video_id=522931&tmdb=1`
    
4.  You can request for a TV series episode by its IMDB ID by using this format: `https://yourwebsite.com/se_player.php?video_id=tt2861424&s=5&e=5` where 's' is the season number and 'e' is the episode number
    
5.  You can request for a TV series episode by its TMDB ID by using this format: `https://yourwebsite.com/se_player.php?video_id=60625&tmdb=1&s=5&e=5` where 's' is the season number and 'e' is the episode number
    

Note
----

You may also have to configure your browser settings to allow it to play the movie file that you want to stream.

If you have any issues, please feel free to submit an issue on the GitHub page or contact the author.

Please note that this script is for personal use only, and streaming copyrighted movies or TV series without permission may be illegal in some countries.
