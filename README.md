# Song Recommendation Program

This project provides a Python script to fetch song recommendations using the Shazam API. Given a song title, the script retrieves a list of songs that match the query and provides relevant details about each song.

## Features

- Search for songs using the Shazam API.
- Retrieve song recommendations based on a given title.
- Fetch details such as song name, artist, and more.

## Technologies

- Python
- `requests` library for making HTTP requests.
- Shazam API for fetching song data.

## Usage

1. Install the required Python libraries:
    ```bash
    pip install requests
    ```

2. Replace the `X-RapidAPI-Key` in the script with your own API key from [RapidAPI](https://rapidapi.com/).

3. Run the script and provide a song title to fetch recommendations:
    ```bash
    python song.py
    ```

## Disclaimer

Make sure to handle your API key securely and comply with all terms of use provided by the Shazam API.

