# Spotify-Clone-HTML-CSS-JS
Core Functionalities:

Song Library: 
It fetches songs from folders on a server (likely a local server running on port 3000) using Live Server.

Album Display: 
It retrieves album information and displays album cards using displayAlbums().

Song Playback: 
It creates an Audio object, sets the source (src) to the song URL, and plays/pauses the music using playMusic().

Playlist Management: 
It retrieves songs from a folder, displays them in a list, and allows selection for playback.

Time Display: 
It updates the current time and total duration of the song using currentSong.currentTime and currentSong.duration.

Progress Bar: 
It displays a progress bar that updates based on the current playback position and allows seeking by clicking on it.

Volume Control: 
It implements a volume slider that adjusts the currentSong.volume property.

Mute Button: 
It mutes/unmutes the audio by setting the volume to 0 or a default value.

Previous/Next Tracks: 
It provides buttons to switch between songs in the current playlist.


Additional Features:

Song Information: 
It displays the title of the currently playing song using document.querySelector(".songinfo").innerHTML.

Responsive Design: 
It handles responsiveness by adjusting the navigation menu position based on user interaction.
Overall, the code demonstrates a solid foundation for a song application.
 
