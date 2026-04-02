# LemonEye
A Python script that sends an audio reminder every 20 minutes, for those who want to use the 20-20-20 rule to protect their eyes.

## Prerequisites
- ffmpeg
- pydub
- pyaudio

## Setup (if you don't have the prerequisites)
1. First, install the latest version of python from python.org.
2. Then using powershell or terminal, install pydub and pyaudio packages. (pip install *)
3. Install ffmpeg, using the instructions on ffmpeg.org/download.
4. Download the code, extract the zip file, and click on lemoneye.pyw to run the file.

## Setup (if you have the prerequisites)
1. Download the code, extract the zip file, and click on lemoneye.pyw to run the file.

## Customization
You can replace the startup and app_tone audio files with wav files. Just make sure that the startup tone is not too long and that the app_tone is not longer than 30 seconds maximum.
This script can be used to repetitively play any music, but the audio files should be wav files, and the files should be renamed to startup.wav, and app_tone.wav.
You can adjust the waiting duration by changing the time.sleep() line in the python script. Change the duration within parenthesis. (by default it is 1200.0)
