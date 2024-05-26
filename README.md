<div align="center">

# MusicGenreDB

Welcome to **MusicGenreDB**, an archive dedicated to preserving and extending the original work of Glenn McDonald, the former Data Alchemist at Spotify, known for his project [Every Noise at Once](https://www.everynoise.com/). This repository aims to maintain and potentially expand on the intricate genre classifications that McDonald created, ensuring the longevity and accessibility of this valuable data.

</div>

## Project Overview

**MusicGenreDB** is an extensive collection of 6,291 genre-shaped distinctions as categorized by Spotify. Each song in this repository is associated with a unique ID that links it to detailed metadata. This project serves as an archive and aims to possibly introduce new features in the future to enhance the original concept.

<div align="center">

## ☕ [Support my work on Ko-Fi](https://ko-fi.com/thatsinewave)

</div>

## Data Structure

The repository contains two main components:

1. **songs/**: A folder with 6,291 audio files. Each file is named with a number corresponding to its ID.
2. **songs_data.json**: A JSON file containing metadata for each song. The structure of the JSON file is as follows:

```json
[
    {
        "id": "SONG ID",
        "genre": "SONG GENRE",
        "url": "SONG URL",
        "title": "ARTIST - SONG NAME",
        "color": "CHOSEN COLOR"
    }
]
```

## How to Use

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/MusicGenreDB.git
    cd MusicGenreDB
    ```

2. **Explore the data**: You can browse the `songs/` folder to access the audio files directly or use the `songs_data.json` file to retrieve detailed information about each song.

3. **Listen to the samples**: Each song entry in `songs_data.json` includes a URL to a Spotify MP3 preview.

## Contributing

We welcome contributions to **MusicGenreDB**! If you have ideas for new features, improvements, or just want to fix a bug, feel free to submit a pull request or open an issue.

<div align="center">

## [Join my discord server](https://discord.gg/2nHHHBWNDw)

</div>

## Credits

All credit for the data itself goes to Glenn McDonald and the artists and bands who created the music. This project is a tribute to their work and aims to preserve and expand upon it.

- Email: [glenn.mcdonald@furia.com](mailto:glenn.mcdonald@furia.com)
- LinkedIn: [glenn mcdonald](https://www.linkedin.com/in/glenn-mcdonald-ab3b36/)
- Twitter: [glenn_mcdonald](https://x.com/glenn_mcdonald)
- Threads: [glennmcdonald](https://www.threads.net/@glennmcdonald)
- Bluesky: [glenn_mcdonald](https://bsky.app/profile/glennmcdonald.bsky.social)
- Mastodon: [@glenn_mcdonald@techhub.social](https://techhub.social/@glenn_mcdonald)
- Instagram: [glennmcdonald](https://www.instagram.com/glennmcdonald/)
- Spotify: [glenn mcdonald](https://open.spotify.com/user/glennpmcdonald)
- Facebook: [glenn mcdonald](https://www.facebook.com/glenn.furia.mcdonald)

## License

This project is licensed under the [MIT License](LICENSE).
