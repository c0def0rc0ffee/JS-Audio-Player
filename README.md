#  jQuery Audio Player

A lightweight jQuery-based audio player for playing and managing a playlist of audio files. Built with `Plyr` for enhanced audio controls and compatibility.

---

##  Features

- **Playlist Navigation**: Play, pause, and navigate through multiple tracks.
- **Media Controls**: Basic controls for play, pause, mute, volume, and seeking.
- **Now Playing Indicator**: Displays the current track title and playback status.
- **Audio Format Support**: Compatible with `.mp3` and `.ogg` formats.

---

##  Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/c0def0rc0ffee/jquery-audio-player.git
   cd jquery-audio-player
2. **HTML Setup**:
   Include jQuery and Plyr in your HTML file:
   ```html
   <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
   <script src="https://cdn.plyr.io/3.6.8/plyr.polyfilled.js"></script>
   <link rel="stylesheet" href="https://cdn.plyr.io/3.6.8/plyr.css" />
3. **Add Playlist Tracks**:
   Update the `tracks` array in the JavaScript code to add your audio files. Each track requires a `name`, `duration`, and `file` path.
4. **Start the Player**:
   Open `index.html` in your browser to start playing audio files!
---

##  Dependencies

- **jQuery**: For DOM manipulation and event handling.
- **Plyr**: Provides enhanced audio controls and media player UI.
