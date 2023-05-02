# SpotifyPictureHelper

Link: [Spotify Picture Helper](https://github.com/daisyye0730/SpotifyPictureHelper)

Description: This is a library of helper functions that allows users to process images in Spotify.
Some tasks that it performs include:

process_user_profile_pic: extracts user profile picture given its html

get_public_playlists_albums: extracts all public playlist album covers from a user's html page

get_individual_album_covers_from_mosaic: extracts four individual cover photos from a mosaic cover photo

get_playlist_profile_pic: extracts the profile picture from a playlist

process_artist_album: extracts all the album covers of an artist

make_request: accepts a html string and requests a session with the html with a response code

get_soup: accepts the return object from make_request and parses into content acceptable in tasks 1-5
