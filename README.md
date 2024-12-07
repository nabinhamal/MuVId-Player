# 🎵 MuVid Player

<div align="center">

![MuVid Player](./assets/icon.png)

A powerful and modern media player built with React Native and Expo.

[![Built with Expo](https://img.shields.io/badge/Built%20with-Expo-4630EB.svg?style=flat-square&logo=EXPO&labelColor=f3f3f3&logoColor=000)](https://expo.dev/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](LICENSE)
[![React Native](https://img.shields.io/badge/React%20Native-v0.76.3-blue.svg?style=flat-square&logo=react)](https://reactnative.dev/)

[Download APK](https://expo.dev/accounts/d3viil/projects/muvid/builds/0a3df90b-5d0c-49cc-ac3b-ef6a61efd13d) · [Report Bug](https://github.com/yourusername/muvid/issues) · [Request Feature](https://github.com/yourusername/muvid/issues)

</div>

## ✨ Features

### 🎵 Audio Playback
- Background audio playback support
- Media controls in notification
- Playlist management
- Equalizer and audio effects
- Shuffle and repeat modes

### 🎥 Video Playback
- Support for multiple video formats
- Full-screen playback
- Picture-in-Picture mode
- Video playlist support
- Thumbnail generation

### 📱 User Interface
- Modern and intuitive design
- Custom bottom sheet player
- Gesture controls
- Dark/Light theme support
- Responsive layout
- Custom drawer navigation

### 🔧 Technical Features
- File system access
- Media library integration
- Background task support
- Document picker integration
- Notification system
- YouTube video support

## 🛠️ Architecture

### Component Structure
```
app/
├── (tabs)/               # Tab navigation
├── components/           # UI Components
│   ├── AudioPlayer      # Audio playback handling
│   ├── VideoPlayer      # Video playback handling
│   ├── PlayerBottomSheet # Custom bottom sheet
│   ├── MediaList        # Media file listing
│   ├── Drawer          # Navigation drawer
│   └── YouTubeModal    # YouTube integration
├── context/             # App context providers
├── providers/           # Service providers
└── services/           # Business logic
```

## 🚀 Getting Started

### Prerequisites
- Node.js >= 14
- npm or yarn
- Expo CLI
- Android Studio (for Android development)
- Xcode (for iOS development)

### Installation

1. Clone the repository
   ```bash
   git clone <repository-url>
   ```

2. Install dependencies
   ```bash
   cd muvid
   npm install
   ```

3. Start the development server
   ```bash
   npx expo start
   ```

## 📱 Usage Guide

### Playing Media Files
1. Grant necessary permissions when prompted
2. Navigate to the media library
3. Select a file to play
4. Use the bottom sheet player controls

### Managing Playlists
1. Long press on media items
2. Select "Add to Playlist"
3. Choose existing playlist or create new

### YouTube Integration
1. Open YouTube modal
2. Paste video URL
3. Enjoy seamless playback

## ⚙️ Configuration

### Build Configuration (eas.json)
```json
{
  "build": {
    "development": {
      "developmentClient": true,
      "distribution": "internal",
      "android": {
        "buildType": "apk",
        "resourceClass": "medium"
      }
    }
  }
}
```

### Required Permissions
- Media Library Access
- File System Access
- Internet Access
- Background Audio
- Notifications

## 🤝 Contributing

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Expo](https://expo.dev/)
- [React Native](https://reactnative.dev/)
- [React Native Track Player](https://react-native-track-player.js.org/)
- [Expo AV](https://docs.expo.dev/versions/latest/sdk/av/)

---

<div align="center">
Made with ❤️ by Nabin Hamal

[⭐️ Star this project](https://github.com/nabinhamal/muvid)
</div>
