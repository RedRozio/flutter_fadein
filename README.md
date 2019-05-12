# Flutter Fade-In [![pub package](https://img.shields.io/pub/v/flutter_fadein.svg)](https://pub.dartlang.org/packages/flutter_fadein)

Simple Flutter widget to fade-in your widgets once they are mounted.

Supports Material & Cupertino widgets.

[Pub](https://pub.dartlang.org/packages/flutter_fadein) - [API Docs](https://pub.dartlang.org/documentation/flutter_fadein/latest/) - [GitHub](https://github.com/Cretezy/flutter_fadein)

## Install

Add this as a dependency in your `pubspec.yaml`:

```yaml
dependencies:
  flutter_fadein: ^1.0.0
```

## Usage

```dart
import 'package:flutter_fadein/flutter_fadein.dart';

FadeIn(
  child: Text("This will be faded-in!"),
  // Optional paramaters
  duration: Duration(milliseconds: 250),
  curve: Curves.easeIn,
)
```
