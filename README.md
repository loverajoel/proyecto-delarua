#Magic Playlist
// Get the playlist of your dreams based on a song

Start with a seed song, the algoritm will search top relational tracks and make a playlist.
Magic Playlist let you play 30 second of preview for each song. Edit the playlist and save in you profile.
Only using the Spotify API.

Type the name of your favourite song and see how the algoritm return you a playlist.

#Features
- Create an Awesome playlist based on a song
- Play audio preview (30 seconds)
- Save playlist in Spotify
- Share playlist

#Algorithm Overview
- Get track, and extract his `popularity`
- From track artist, get related artists
- Get top tracks(max:20) from each related artist
- Sort all tracks from popularity(ASC)
- Alternate 1:1
- Select the batch(30) based in the first track popularity
- Sort by poularity
- Alternate

#Stack
- ES6
- Flux
- React
- Spotify-SDK

#Spotify API

If you're curious what data you can use inside player just take a look into official SoundCloud Developers docs for tracks.


Made with :heart: from Córdoba, Argentina.
