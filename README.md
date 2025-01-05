# Music Player Web App

This is a simple web-based music player built with HTML, CSS, and JavaScript. It allows users to play, pause, skip through songs, and control the volume. Users can also interact with a playlist to add and remove songs, making the music experience more personalized.


![Screenshot 2025-01-05 130619](https://github.com/user-attachments/assets/1c7543e3-40cd-4b41-8ce7-cc076649a6b1)



## Features

- Play, Pause, Skip, and Previous buttons for controlling music playback.
- Volume control with a slider.
- Playlist display and interaction, including adding and removing songs.
- Song progress bar to track the current song's progress.
- Ability to loop songs or the entire playlist.
- ![Screenshot 2025-01-05 130640](https://github.com/user-attachments/assets/caf85144-6e24-4f0f-9ff4-0cd2c489ea7b)


## Tech Stack

- **HTML**: For the structure of the music player interface.
- **CSS**: For styling the app and making it visually appealing.
- **JavaScript**: To implement the functionality of the music player and playlist.
- **Material Icons**: For adding icons (e.g., play, pause, skip) to the interface.

## Requirements

To run this project, you need a browser that supports HTML5 and JavaScript. No backend or server-side setup is required.

## Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/music-player.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd music-player
   ```

3. **Open the `index.html` file in your browser**:
   Simply open the `index.html` file in any modern browser to run the music player.

## File Structure

```
music-player/
│
├── index.html         # Main HTML file
├── style.css          # Styles for the music player
├── script.js          # JavaScript for music player functionality
├── img/               # Folder containing album cover images
│   ├── song1.jpg
│   ├── song2.jpg
│   └── song3.jpg
└── songs/             # Folder containing song files (mp3 format)
    ├── song1.mp3
    ├── song2.mp3
    └── song3.mp3
```

## How to Use

1. **Play/Pause**: Click on the play button to start the song, and it will change to a pause button. Click on the pause button to pause the song.
2. **Skip to Next Song**: Click on the "Next" button to go to the next song in the playlist.
3. **Previous Song**: Click on the "Previous" button to go back to the previous song.
4. **Volume Control**: Adjust the volume using the slider in the "Volume" section.
5. **Progress Bar**: The progress bar updates as the song plays. You can also click on the progress bar to seek to a specific point in the song.
6. **Playlist**: Click on the "Playlist" icon to open the music list. You can add the current song to the playlist by clicking the "Add to Playlist" icon, and remove songs by clicking the "Remove" button next to each song in the playlist.

## Customization

- **Songs**: To add more songs, add them to the `songs/` directory and update the `playlist` array in `script.js` with the correct paths to the audio files and album cover images.
- **Styling**: Customize the look of the music player by modifying the `style.css` file.

## Troubleshooting

1. **Audio Not Playing**:
   - Ensure that your browser supports HTML5 audio.
   - Make sure that the audio files are in the correct path and accessible.

2. **Icons Not Displaying**:
   - Ensure that the Material Icons library is properly linked in the `index.html` file.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository, make changes, and submit a pull request.

## License

This project is open-source and available under the MIT License.
```

You can save this text as `README.md` and add it to your project repository.
