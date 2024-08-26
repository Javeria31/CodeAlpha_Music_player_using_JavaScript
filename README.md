# CodeAlpha_Music_player_using_JavaScript

# Music Player

Welcome to the **Music Player** project! This is a simple, customizable music player built with HTML, CSS, and JavaScript. The player features basic functionalities such as play/pause, next/previous track, volume control, and shuffle/repeat modes. It also includes a visually appealing UI with dynamic background effects and a rotating album art feature.

## Features

- **Play/Pause**: Play or pause the current track.
- **Next/Previous Track**: Skip to the next or previous track in the playlist.
- **Shuffle Mode**: Play tracks in a random order.
- **Repeat Mode**: Repeat the current track.
- **Volume Control**: Adjust the volume of the audio.
- **Seek Control**: Seek through the track with a slider.
- **Dynamic Background**: The background color changes randomly with each track.
- **Rotating Album Art**: The album art rotates when a track is playing.
- **Loader Animation**: A wave animation shows when a track is playing.

## Getting Started

### Prerequisites

To run this project, you need a web browser that supports HTML5 and CSS3.

### Installation

1. **Clone the repository**:

   git clone https://github.com/your-username/music-player.git
Navigate to the project directory:


cd music-player
Open index.html in your preferred web browser:


open index.html
or simply drag and drop the index.html file into your browser.

Adding Your Own Music
To add your own music to the player:

Add your music files to the music directory.
Add corresponding album art images to the Images directory.
Update the music_list array in script.js with the details of your new tracks, including the name, artist, music file path, and image file path.
Example:

const music_list = [
    {
        img: 'Images/1.jpeg',
        name: 'Song Title',
        artist: 'Artist Name',
        music: 'music/your-song.mp3'
    },
    // Add more tracks here...
];
Customization
You can customize the look and feel of the player by modifying the style.css file. Change colors, fonts, and other styles to match your preferences.

Known Issues
Ensure all music files and images are correctly linked in the music_list array. Incorrect paths will result in broken functionality.
The shuffle function only works properly when there are multiple tracks in the playlist.
License
This project is open-source and free to use under the MIT License. Feel free to contribute or fork the repository.

Acknowledgments
Icons: Icons used in this project are from Flaticon.
Inspiration: This project was inspired by various music player designs available on the web.
Contact
If you have any questions or suggestions, feel free to open an issue or reach out via javmajsha@gmail.com.

