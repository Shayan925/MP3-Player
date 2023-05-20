# Arduino Uno MP3 Player with MP3 Shield
### This project is an MP3 player created using an Arduino Uno and an MP3 shield. It allows you to play audio files in MP3 format from an SD card, providing an interactive and enjoyable audio playback experience. You can view a demonstration by clicking on the image below.

<br>

[<img src="https://img.youtube.com/vi/W-WYVrsH0HQ/hqdefault.jpg" width="40%">](https://www.youtube.com/watch?v=W-WYVrsH0HQ)

## Features
- MP3 Playback: The Arduino Uno, coupled with the MP3 shield, enables the playback of MP3 audio files with high audio quality.
- SD Card Support: The MP3 player reads audio files from an SD card, allowing you to store and organize your favorite tracks conveniently.
- User Interface: The project includes buttons and a serial monitor to provide a user-friendly interface for controlling playback, volume, track selection, and more

## Hardware Requirements
To build and use the Arduino Uno MP3 Player, you will need the following components:
- Arduino Uno board
- MP3 shield compatible with the Arduino Uno
- SD card
- Audio amplifier circuit
- Control buttons (e.g., play/pause, next, previous, volume control)
- Speakers or headphones for audio output
- For a singular speaker you will need to create the stereo to mono circuit as well.

## Installation and Usage
- Connect the MP3 shield to the Arduino Uno board, ensuring that all the pins are correctly aligned.
- Connect the control buttons to the Arduino Uno and wire them to the corresponding pins defined in the code.
- Upload the Arduino sketch provided in the project repository to the Arduino Uno using the Arduino IDE or your preferred programming environment.
- Prepare an SD card by formatting it as FAT32 and copying your desired MP3 audio files onto it with names like 'track001.mp3'
- Insert the SD card into the SD card module connected to the MP3 shield.
- Use the control buttons and the serial monitor to navigate through your MP3 files, adjust the volume, and control playback.
- Enjoy your favorite music or audio tracks with the Arduino Uno MP3 Player!

