# Music Player

Music Player built using HTML, CSS and JavaScript — a simple, responsive audio player you can run locally and customize with your own songs.


## Screenshot

![Music Player Screenshot](./Screenshot%202024-06-15%20205046.png)


## Features

- Play, pause, next and previous controls
- Progress bar with seek support
- Display track title and current time / duration
- Responsive layout — works on desktop and mobile
- Easy to add or remove tracks (see the music folder)


## Getting started

1. Clone the repository:

   git clone https://github.com/BinaryVortex/Music-Player.git

2. Open `index.html` in your browser (double-click the file or serve with a simple HTTP server):

   - Option A (double-click): open `index.html` directly in your browser.
   - Option B (simple server): from the project folder run `npx http-server` or `python -m http.server` and open http://localhost:8080.


## Usage

- Use the Play/Pause button to start or stop the current track.
- Use Next / Previous to change tracks.
- Click or drag the progress bar to seek inside the track.
- Add audio files to the `music/` folder and update the track list in `script.js` to include them.


## Project structure

- `index.html` — markup and player container
- `style.css` — styles and responsive layout
- `script.js` — player logic (controls, progress, track list)
- `music/` — folder for audio files
- `Screenshot 2024-06-15 205046.png` — UI screenshot used in this README


## Customization

- To add songs: put .mp3 (or supported audio) files into the `music/` folder and add entries to the tracks array in `script.js` with the file name, title, and artist.
- To change appearance: edit `style.css`.
- To extend functionality: modify `script.js` to support playlists, shuffle, repeat, or visualizers.


## Contributing

Contributions are welcome! Open an issue or submit a pull request with improvements or bug fixes. Please include a short description of your changes.


## License

This project does not include a license file. If you want others to use or contribute under specific terms, consider adding an open-source license (for example MIT).


## Contact

Created by BinaryVortex.

