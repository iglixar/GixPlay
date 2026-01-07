<div align="center">
  <img src="https://ik.imagekit.io/sbsjhivv8/IMG-20260107-WA0003.jpg" alt="Gixplay Logo" width="120" style="border-radius: 50%;" />
  <h1>Gixplay</h1>
  <p><strong>A mobile-first, YouTube-powered music streaming PWA with a pure black theme, offline capabilities, and deep personal analytics.</strong></p>

  <p>
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
    <img src="https://img.shields.io/badge/IndexedDB-005395?style=for-the-badge&logo=sqlite&logoColor=white" />
    <img src="https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white" />
  </p>
</div>

---

## About Gixplay

**Gixplay** is a privacy-first, mobile-optimized music streaming Progressive Web App designed for personal use.  
It allows users to search, play, and organize music sourced from YouTube while keeping **all data fully local** to the device.

No accounts  
No cloud sync  
No tracking  

Your playlists, history, and analytics never leave your device.

---

## Key Features

- **[ Streaming ] YouTube-Based Playback**  
  Search for music or add tracks via direct YouTube links.

- **[ UI ] Pure Black OLED Interface**  
  Battery-friendly, distraction-free interface optimized for night usage.

- **[ Storage ] Local-Only Data**  
  All playlists, tracks, and listening history are stored in IndexedDB.

- **[ App ] Installable Progressive Web App**  
  Runs like a native app with offline access to saved data.

- **[ Playback ] Background Audio Support**  
  Music continues while the app is minimized (browser dependent).

- **[ Playlists ] Fast Management**  
  Create and manage playlists using gesture-based controls.

- **[ Analytics ] Listening Insights**  
  Weekly, monthly, yearly charts with streaks and activity heatmaps.

- **[ Backup ] Data Portability**  
  Export and import the full library using a single file.

- **[ Privacy ] Zero Tracking**  
  No login, no ads, no telemetry, no remote database.

---

## Architecture Overview

- **Search & Metadata**  
  Uses public YouTube data endpoints for discovery and metadata.

- **Playback Engine**  
  Streams audio through a controlled YouTube iframe player optimized for background usage.

- **Local Database**  
  IndexedDB stores tracks, playlists, and analytics for instant access and offline continuity.

- **Analytics System**  
  Playback events are processed locally to generate charts and usage insights.

---

## Platform Support

- Mobile browsers (Android / iOS)
- Desktop browsers
- Installable PWA
- Trusted Web Activity (TWA) compatible

---

## Usage Notice

Gixplay is intended for **personal and educational use**.  
It does not host, redistribute, or modify media content and relies on publicly accessible web playback mechanisms.

---

## Project Status

- Actively developed
- Private distribution
- Not open source

---

© Gixplay — Personal music, full control.
