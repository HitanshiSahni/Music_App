# Simple Android Music Player

A lightweight, native Android music player application built with Java[cite: 2]. This project serves as a standalone audio player with pre-loaded tracks, custom media controls, and integrated album art[cite: 2].

## ✨ Features

*   **Core Playback Controls:** Play, pause, skip forward, and go back to previous tracks using custom UI buttons[cite: 2].
*   **Pre-bundled Audio:** Includes embedded `.mp3` tracks (such as "Montero" and "Lag Ja Gale") played directly from the raw resources directory[cite: 2].
*   **Dynamic UI Elements:** Displays corresponding album art (`song1.jpg` to `song4.jpg`) for the currently playing track[cite: 2].
*   **Volume Management:** Includes visual indicators and controls for maximum and minimum sound levels[cite: 2].
*   **Single-Activity Architecture:** A streamlined user interface handled entirely within `MainActivity.java`[cite: 2].

## 🛠️ Tech Stack

*   **Language:** Java[cite: 2]
*   **Platform:** Android SDK
*   **IDE:** Android Studio
*   **UI/UX:** XML-based layouts (`activity_main.xml`)[cite: 2]
*   **Build System:** Gradle (Kotlin DSL)[cite: 1]

## 📂 Project Structure Highlights

The application relies on standard Android resource directories for media management:
*   `app/src/main/java/.../MainActivity.java`: Contains the core logic for the MediaPlayer and UI interactions[cite: 2].
*   `app/src/main/res/raw/`: Stores the bundled `.mp3` audio files[cite: 2].
*   `app/src/main/res/drawable/`: Contains the custom vector/PNG icons for the playback controls and the track cover art[cite: 2].

## 🚀 Getting Started

To run this project locally on your machine:

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>

2. **Open in Android Studio:**
    Launch Android Studio, select Open, and navigate to the root directory of this cloned project.

3. **Sync and Build:**
    Allow Gradle to sync the project dependencies.

4. **Run:**
    Connect an Android device via USB or start an Android emulator, then click the Run button to install the app.
