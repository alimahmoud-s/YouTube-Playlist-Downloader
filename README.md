##YouTube Downloader App

#This project is a simple application that allows users to download YouTube playlists using the yt-dlp library. It prompts the user for a playlist URL and handles the download process with error handling.

##Features

#Download entire YouTube playlists

#Download videos in preferred resolution (480p, 720p, 1080p, etc.)

#Download audio-only versions of videos

#Supports concurrent fragment downloads for faster performance

Allows users to specify a proxy for restricted network environments

Displays real-time download progress with percentage tracking

Custom save directory selection

Error handling for download issues

Requirements

Python 3.x

yt-dlp library

Installation

Clone the repository:

git clone https://github.com/alimahmoud-s/YouTube-Playlist-Downloader.git

Navigate to the project directory:

cd youtube-downloader-app

Install the required dependencies:

pip install -r requirements.txt

Usage

Run the application:

python src/youtube_script.py

Select the download format (video or audio).

If downloading video, specify the preferred resolution.

Enter a proxy if required.

Enter the playlist URL when prompted.

The files will be saved in the selected directory.

License

This project is licensed under the MIT License.
