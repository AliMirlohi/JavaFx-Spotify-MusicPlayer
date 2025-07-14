# JavaFx-Spotify-MusicPlayer

A robust desktop music player inspired by Spotify, built with Java and JavaFX. This project provides a feature-rich, visually appealing media player with playlist management, artist and track browsing, and user accounts, all designed for an engaging and modern music experience.

## Features

- **Modern UI:** Built using JavaFX, offering a sleek and responsive interface.
- **User Accounts:** Supports listeners, podcasters, and admin roles, each with distinct privileges and dashboards.
- **Playlist Management:** Create, manage, and play custom playlists. Add tracks to playlists directly from the player.
- **Audio Playback:** Stream and play audio files with a customizable play bar, cover art, and lyrics display.
- **Artist & Track Browsing:** Search, filter, and sort music by artist, genre, popularity, and more.
- **Lyrics & Podcast Support:** Display lyrics for songs or captions for podcasts.
- **Subscription Models:** Includes account credit management and subscription plans (see code for details).
- **Admin Dashboard:** Admin users may view reports, manage artists and tracks, and monitor most-liked audios.
- **Visual Feedback:** Success and warning popups for user actions.
- **Extensible Architecture:** Organized using MVC principles for easy maintenance and extension.


## Getting Started

### Prerequisites

- Java 11 or higher
- JavaFX SDK
- Maven or Gradle (recommended for dependency management)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/AliMirlohi/JavaFx-Spotify-MusicPlayer.git
   cd JavaFx-Spotify-MusicPlayer
   ```

2. **Download JavaFX SDK:**  
   [Download JavaFX](https://gluonhq.com/products/javafx/)

3. **Setup your IDE:**  
   - Add JavaFX SDK to your project libraries.
   - Configure VM options for JavaFX (see official docs).

4. **Build and Run:**
   - Using Maven:
     ```sh
     mvn javafx:run
     ```
   - Or run the `HelloApplication` class from your IDE.

## Usage

- **Login/Sign Up:** Start the application and create or log in to your account.
- **Browse Music:** Search for tracks, browse by artist or genre.
- **Play Music:** Select a track to play. View lyrics/captions and cover art.
- **Create Playlists:** Add your favorite tracks to custom playlists.
- **Admin Functions:** Access admin dashboard for management features (if logged in as admin).

## Project Structure

```
src/
  main/
    java/
      GUI/                 # UI controllers & views
      controller/          # Business logic controllers
      model/               # Data models (Audio, Playlist, UserAccount, etc.)
      org/example/firstprojphase2/HelloApplication.java   # Main application entry point
    resources/             # FXML files, images, and other assets
```

## Extending & Contributing

- Open for contributions! Fork the repo and submit pull requests.
- For bug reports or feature requests, please open a GitHub issue.



## Author

Ali Mirlohi  
GitHub: [AliMirlohi](https://github.com/AliMirlohi)

---

*Inspired by Spotify, built for learning and experimentation.*
