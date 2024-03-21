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

## Styling

```css
/* Add some styling to make it visually appealing */

body {
  font-family: Arial, sans-serif;
  background-color: #f8f9fa;
  color: #333;
}

.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  background-color: #fff;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1 {
  text-align: center;
  color: #007bff;
}

h2 {
  color: #007bff;
}

ul {
  list-style: none;
  padding: 0;
}

li {
  margin-bottom: 10px;
}

.progress-bar {
  width: 100%;
  height: 10px;
  background-color: #ddd;
  border-radius: 5px;
  margin-bottom: 20px;
}

.progress {
  height: 100%;
  background-color: #007bff;
  border-radius: 5px;
}

.volume-slider {
  width: 100px;
}



 
