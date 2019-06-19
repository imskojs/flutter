* Download unzip and include path;
```bash
# .bash_profile
export NO_PROXY=127.0.0.1,localhost # Fixes a connection to emulator
export FLUTTER_HOME=/Users/S/Library/flutter
PATH=${PATH}:${FLUTTER_HOME}/bin
```

* `flutter doctor` for a guide on setting up dependencies.

* Setup android virtual device by: Create Project in Android Studio -> Tools -> AVD Manager -> Create Virtual Device
Create API level 28 as 29 seems to have a connection problem.

* Start emulator, `flutter create APP_NAME`, `flutter run`