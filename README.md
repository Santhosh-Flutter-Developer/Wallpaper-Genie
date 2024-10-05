# Wallpaper Genie 📱🖼️

**Wallpaper Genie** is a Flutter-based app that lets users explore a vast collection of high-quality wallpapers fetched from the **Pixabay API**. With an intuitive interface, it allows users to search, view, download, and set wallpapers on their devices easily.

## Features 🌟

- 🖼️ **Wallpapers from Pixabay**: Fetch and display wallpapers using the Pixabay API.
- 🔍 **Search functionality**: Search for wallpapers by keywords (e.g., nature, animals, etc.).
- ❤️ **Favorites**: Save your favorite wallpapers for quick access.
- 📥 **Download wallpapers**: Download any wallpaper directly to your device.
- 🌓 **Dark/Light Mode**: Toggle between light and dark themes.
- 🎨 **Fluid and responsive UI**: A seamless user experience with optimized scrolling.

## Screenshots 📸
![Apple iPhone 11 Pro Max Presentation (1)](https://github.com/user-attachments/assets/16a9b5cf-c149-4ff3-80ad-72ec848327f7)


## Getting Started 🚀

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- A [Pixabay API Key](https://pixabay.com/api/docs/) (Free sign-up required)

### Installation

1. **Clone the repository**:
   
   ```bash
   git clone https://github.com/yourusername/wallpaper_genie.git
   cd wallpaper_genie

2. **Install dependencies**:
   
   ```bash
   flutter pub get

3. **Set up Pixabay API key**:

- Open the lib/services/api_service.dart file.
- Replace your_pixabay_api_key with your actual Pixabay API key.
   
   ```bash
   const String apiKey = 'your_pixabay_api_key';

4. **Run the app**
   
    ```bash
   flutter run

## Dependencies 📦
This project uses the following Flutter packages:

- [http]() for handling API requests.
- [cached_network_image]() for efficient image caching.
- [provider]() for state management.
- [shared_preferences]() for storing user preferences and favorites.
- [flutter_launcher_icons]() to generate app icons.

## License 📄
This project is licensed under the MIT License. See the [LICENSE]() file for more details.
