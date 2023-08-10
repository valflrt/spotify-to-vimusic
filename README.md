# spotify-to-vimusic
## What is this?
Small thing I made to transfer my Liked playlist from Spotify to [ViMusic](https://github.com/vfsfitvnm/ViMusic)
## How do I use?
Export your playlist from Spotify with something like [Spotlistr](https://www.spotlistr.com/) to a text file, using `|` (pipe) as a separator. Fields neeeded are song name and artist. Name the resulting file `songlist.txt`

Go into ViMusic, export a backup, and rename it to `database.db`

Put both of these files in the same folder as `spotifytovimusic.py`, run `pip ytmusicapi thefuzz cutlet`, and run the python script. Once its done you can reimport the database into ViMusic
