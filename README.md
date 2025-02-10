# Chord Extractor
Chord Extractor is a Python application built using Pygame, librosa, and ffmpeg. It is designed to play audio files while dynamically extracting and displaying chords from the music. The application offers various playback controls—including adjustable speed, volume, transposition, and repeat functionality—and organizes chord information on a multi-level interface.

Key Features
Audio Playback:
Plays audio files (MP3 and WAV) with controls for pausing, skipping, and repeating.

Chord Extraction:
Uses librosa to analyze the harmonic content of the audio and determine the underlying chords. The chords are then displayed on a three-level (vertical) interface.

Transposition and Speed Adjustment:
Allows real-time transposition of the audio along with corresponding updates to the chord display, as well as changing the playback speed.

Graphical User Interface:
The UI is developed with Pygame and includes a file manager and control buttons. All controls are represented by icons stored in a resources folder.

Temporary File Management:
The program creates and cleans up temporary audio files during playback adjustments.

Getting Started
To run the application on Windows:

Install the required libraries (e.g., Pygame, librosa, soundfile, Pillow) in your Python environment.
Ensure ffmpeg is installed and update the FFMPEG_PATH in the code accordingly.
Place all necessary icon files (such as PlayPause.png, fast.png, Louder.png, etc.) in a folder named resources in the same directory as the script.
Run the main Python script.
For packaging the application into an executable (using PyInstaller or a similar tool), refer to the relevant documentation.

Monetization & Future Work
The application is designed to be a foundation for interactive audio processing and could be extended (e.g., ported to Android or integrated with ad networks) to reach a broader audience.
