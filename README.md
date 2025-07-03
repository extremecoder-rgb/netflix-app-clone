# Netflix Clone

A Flutter application that mimics the core UI and features of Netflix, allowing users to browse, search, and view details about movies and TV series. This project uses the [TMDB API](https://www.themoviedb.org/documentation/api) for fetching movie and TV data.

## Features

- **Splash Screen**: Animated splash screen with Netflix branding.
- **Bottom Navigation Bar**: Quick access to Home, Search, and New & Hot sections.
- **Home Screen**:
  - Carousel of top-rated TV series.
  - Now Playing and Upcoming Movies sections.
  - Quick access to Search.
- **Search Screen**:
  - Search for movies using TMDB API.
  - View top searches and search results with images and titles.
  - Tap to view detailed information about a movie.
- **New & Hot (More) Screen**:
  - Tabs for "Coming Soon" and "Everyone's Watching".
  - List of upcoming and trending movies/series with images, overviews, and release dates.
- **Movie Details**: (Accessible from search and lists) View detailed information and recommendations for each movie.

## Screenshots

_Add screenshots of the app here if available._

## Getting Started

### Prerequisites
- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- Dart SDK (comes with Flutter)
- A device or emulator (Android, iOS, Web, Windows, macOS, Linux)

### Installation
1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd Netflix-Clone-master
   ```
2. **Install dependencies:**
   ```bash
   flutter pub get
   ```
3. **Run the app:**
   ```bash
   flutter run
   ```
   You can specify a device with `-d` (e.g., `flutter run -d chrome` for web).

### Assets
All required assets (images, Lottie animation, etc.) are included in the `assets/` directory and referenced in `pubspec.yaml`.

### API Key
This project uses a TMDB API key, which is already included in the code for demonstration purposes. For production or public use, you should secure your API key.

## Dependencies
- [flutter](https://flutter.dev/)
- [cupertino_icons](https://pub.dev/packages/cupertino_icons)
- [google_fonts](https://pub.dev/packages/google_fonts)
- [lottie](https://pub.dev/packages/lottie)
- [http](https://pub.dev/packages/http)
- [cached_network_image](https://pub.dev/packages/cached_network_image)
- [carousel_slider](https://pub.dev/packages/carousel_slider)
- [win32](https://pub.dev/packages/win32) (for Windows support)

## Project Structure
- `lib/`
  - `main.dart` - App entry point
  - `screens/` - Main UI screens (Home, Search, New & Hot, Splash, etc.)
  - `services/` - API service for TMDB
  - `models/` - Data models for movies, TV series, search, etc.
  - `widgets/` - Reusable UI components
  - `common/` - Utilities and constants
- `assets/` - Images, Lottie files, and other static assets

## License
This project is for educational purposes and is not affiliated with Netflix. Please respect the TMDB API terms of use. 