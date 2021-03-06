# flutter_vector_icons

[![pub](https://img.shields.io/pub/v/flutter_vector_icons.svg)](https://pub.dev/packages/flutter_vector_icons)
[![gallery](https://github.com/git-touch/flutter-vector-icons/workflows/gallery/badge.svg)](https://git-touch.github.io/flutter-vector-icons/)

Customizable Icons for Flutter. Port of [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons).

View [the gallery built with Flutter Web](https://git-touch.github.io/flutter-vector-icons/)

## Installation

Add `flutter_vector_icons` as a [dependency in your pubspec.yaml file](https://flutter.dev/docs/development/packages-and-plugins/using-packages)

## Usage

```dart
import 'package:flutter/material.dart';
import 'package:flutter_vector_icons/flutter_vector_icons.dart';

class MyWidget extends StatelessWidget {
  Widget build(BuildContext context) {
    return IconButton(
      // Variable name is the same as font name:
      //
      // AntDesign
      // Entypo
      // EvilIcons
      // Feather
      // FontAwesome
      // Foundation
      // Ionicons
      // MaterialCommunityIcons
      // MaterialIcons
      // Octicons
      // SimpleLineIcons
      // Zocial
      // FontAwesome5Brands
      // FontAwesome5Regular
      // FontAwesome5Solid

      icon: Icon(MaterialCommunityIcons.star),
      onPressed: () {
        print('Star it');
      },
    );
  }
}
```

## Development

```sh
cd tool
npm install
node index.js
```

## Credits

- [react-native-vector-icons](https://github.com/oblador/react-native-vector-icons)

## License

MIT
