# Flappy Bird 🐦

**Flappy Bird** is a simple and addictive endless game where the player controls a bird, tapping to fly and avoid obstacles. This project is built using **Flutter** and the **Flame** game engine, featuring smooth gameplay, sound effects, and responsive controls for Android.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Gameplay](#gameplay)
- [Assets](#assets)
- [Packages Used](#packages-used)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Flappy Bird Mechanics**: Tap to control the bird's flight and avoid obstacles.
- **Responsive Gameplay**: Works smoothly on Android devices.
- **Sound Effects**: Includes sound effects for flapping, collision, and game over.
- **Custom Fonts**: Uses a retro-styled game font to enhance the user experience.
- **Endless Gameplay**: The game continues until the bird crashes into obstacles.
- **Cross-platform Compatibility**: Built using Flutter for easy development on Android.

## Installation

To run this project locally on Android, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/flutter-flappy-bird.git
   cd flutter-flappy-bird
   ```

2. **Install dependencies**:
   ```bash
   flutter pub get
   ```

3. **Run the app on Android**:
   ```bash
   flutter run -d android
   ```

## Gameplay

- **Tap the screen**: Tap to make the bird flap its wings and fly upwards.
- **Avoid obstacles**: Navigate through a series of pipes without hitting them.
- **Game Over**: The game ends when the bird collides with an obstacle or falls to the ground.
- **Sound Effects**: Enjoy audio feedback for each tap and collision, enhancing the gameplay experience.

## Assets

This game uses custom assets such as images, audio, and fonts. Ensure you add them to the appropriate directories:

- **Images**: All game-related images should be placed in the `assets/images/` folder.
- **Audio**: Sound effects should be stored in the `assets/audio/` folder.
- **Fonts**: Custom fonts, like the "Game" font used in this project, should be in `assets/fonts/`.

Ensure that the `pubspec.yaml` file includes the following for asset registration:

```yaml
flutter:
  assets:
    - assets/images/
    - assets/audio/

  fonts:
    - family: Game
      fonts:
        - asset: assets/fonts/Game.ttf
```

## Packages Used

- [**Flame**](https://pub.dev/packages/flame) `^1.17.0`: Game engine used for handling game mechanics and sprite rendering.
- [**Flame Audio**](https://pub.dev/packages/flame_audio) `^2.1.2`: For integrating sound effects into the game.
- [**Cupertino Icons**](https://pub.dev/packages/cupertino_icons) `^1.0.6`: For icons used in Android apps.
- [**Flutter Lints**](https://pub.dev/packages/flutter_lints) `^3.0.0`: Recommended lints for Flutter projects.

## Future Enhancements

- **High Score System**: Add functionality to track and display the highest score achieved by the player.
- **Difficulty Scaling**: Introduce increasing difficulty levels as the player progresses.
- **Power-ups**: Implement in-game power-ups to make the game more dynamic.
- **Different Themes**: Add different visual themes and backgrounds to vary the gameplay experience.

## Contributing

Contributions are welcome! If you'd like to improve the game or add new features, feel free to fork the repository and submit a pull request.

1. Fork the repository.
2. Create a new feature branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.
