# Spotify-Clone-HTML-CSS-JS

## Core Functionalities

### Song Library
- Fetches songs from folders on a server using Live Server running on port 3000.

### Album Display
- Retrieves album information and displays album cards using `displayAlbums()`.

### Song Playback
- Creates an `Audio` object, sets the source (src) to the song URL, and plays/pauses the music using `playMusic()`.

### Playlist Management
- Retrieves songs from a folder, displays them in a list, and allows selection for playback.

### Time Display
- Updates the current time and total duration of the song using `currentSong.currentTime` and `currentSong.duration`.

### Progress Bar
- Displays a progress bar that updates based on the current playback position and allows seeking by clicking on it.

### Volume Control
- Implements a volume slider that adjusts the `currentSong.volume` property.

### Mute Button
- Mutes/unmutes the audio by setting the volume to 0 or a default value.

### Previous/Next Tracks
- Provides buttons to switch between songs in the current playlist.

## Additional Features

### Song Information
- Displays the title of the currently playing song.

### Responsive Design
- Handles responsiveness by adjusting the navigation menu position based on user interaction.


