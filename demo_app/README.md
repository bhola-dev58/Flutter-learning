# Assignment 1
## Task: Flutter Installation

| Step                | Options/Details                                                        |
|---------------------|-----------------------------------------------------------------------|
| Install Flutter SDK | Download and install the Flutter SDK                                   |
| Set up IDE          | Android Studio or VS Code                                              |
| Install Plugins     | Flutter, Dart                                                          |
| Device Setup        | Android Emulator or Physical Android device (USB debugging enabled)     |


## Task  I completed
1. Verified Setup
    command : `flutter doctor`
    output:
    ```
    Doctor summary (to see all details, run flutter doctor -v):
    [✓] Flutter (Channel stable, 3.41.3, on Ubuntu 24.04.4 LTS 6.17.0-20-generic, locale
    en_US.UTF-8)
    [✓] Android toolchain - develop for Android devices (Android SDK version 36.1.0)
    [✓] Chrome - develop for the web
    [✓] Linux toolchain - develop for Linux desktop
    [✓] Connected device (2 available)
    [✓] Network resources
    
    ```
2. Created the demo app
    command : `flutter create demo_app`

    directories i Gain:
    ```

    ├── analysis_options.yaml
    ├── android
    │   ├── app
    │   ├── build.gradle.kts
    │   ├── demo_app_android.iml
    │   ├── gradle
    │   ├── gradle.properties
    │   ├── gradlew
    │   ├── gradlew.bat
    │   ├── local.properties
    │   └── settings.gradle.kts
    ├── build
    │   ├── 5bb0dd82b6c53973a3dd349f29f93dc2
    │   ├── app
    │   ├── b2f7e7edd35b3c8d4f463bb8b035ecd8.cache.dill.track.dill
    │   ├── native_assets
    │   ├── native_hooks
    │   └── reports
    ├── demo_app.iml
    ├── ios
    │   ├── Flutter
    │   ├── Runner
    │   ├── RunnerTests
    │   ├── Runner.xcodeproj
    │   └── Runner.xcworkspace
    ├── lib
    │   └── main.dart
    ├── linux
    │   ├── CMakeLists.txt
    │   ├── flutter
    │   └── runner
    ├── macos
    │   ├── Flutter
    │   ├── Runner
    │   ├── RunnerTests
    │   ├── Runner.xcodeproj
    │   └── Runner.xcworkspace
        pubspec.lock
    ├── pubspec.yaml
    ├── README.md
    ├── test
    │   └── widget_test.dart
    ├── web
    │   ├── favicon.png
        │   ├── icons
    │   ├── index.html
    │   └── manifest.json
    └── windows
    ├── CMakeLists.txt
    ├── flutter
    └── runner
    ```

    Run the project using command: `flutter run`
    `Note: I preferred My device using USB debugging`
    

## changes i made in `lib/main.dart`

with this code
```
import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return const MaterialApp(
      home: Scaffold(
        body: Center(
          child: Text('Welcome to my demo app'),
        ),
      ),
    );
  }
}
```


## Output ScreenShot
<img src="https://github.com/bhola-dev58/Flutter-learning/blob/main/Screenshot/Scrrenshot.png" width="400">
