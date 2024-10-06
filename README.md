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
![Apple iPhone 11 Pro Max Presentation (3)](https://github.com/user-attachments/assets/e03d2fee-4f23-41fd-b9ab-064158fe3a5f)



## Getting Started 🚀

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- A [Pixabay API Key](https://pixabay.com/api/docs/) (Free sign-up required)

### Installation

1. **Clone the repository**:
   
   ```bash
   git clone https://github.com/Santhosh-Flutter-Developer/Wallpaper-Genie.git
   cd Wallpaper-Genie

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

- [get](https://pub.dev/packages/get) for state management and routing.
- [http](https://pub.dev/packages/http) for handling API requests.
- [insta_image_viewer](https://pub.dev/packages/insta_image_viewer) for display image in a full-screen, swipe it to dismiss, pinch & zoom.
- [flutter_staggered_grid_view](https://pub.dev/packages/flutter_staggered_grid_view) for a collection of Flutter grids layouts.

## License 📄
This project is licensed under the MIT License. See the [LICENSE]() file for more details.
