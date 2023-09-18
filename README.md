# Billboard 100 to Spotify Playlist Converter

![App Screenshot]()

## Table of Contents

- [Description](#description)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Author](#author)

## Description
This program allows you to create a private Spotify playlist 
containing the Billboard Hot 100 songs from a specific date. It scrapes the 
Billboard website to retrieve the song names and then searches Spotify to 
find corresponding song tracks. Finally, it creates a new private Spotify 
playlist and adds the discovered songs to it.

## Requirements
- Python (3.x recommended)
- BeautifulSoup (`beautifulsoup4`) library
- Requests (`requests`) library
- spotify (`spotify`) library
- Spotify API credentials, which you can obtain by creating an application in 
the Spotify Developer Dashboard.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/laurianerzb/spotify_playlist.git
2. Navigate to the project directory:
   ```bash 
   cd spotify_playlist
3. Run the program
   ```bash
   python main.py

## Usage
- Before running the program make sure to install the required libraries
- replace the parts of code with your own credentials

## Credits
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Spotify Documentation](https://spotipy.readthedocs.io/en/2.22.1/)
- [Spotify Dashboard](https://developer.spotify.com/dashboard/)

## Author
- [laurianerzb](https://github.com/laurianerzb)
