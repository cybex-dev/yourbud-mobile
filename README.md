# YourBud Client Portal

YourBud mobile client portal

## Getting Started

This project depends on Firebase Hosting solution for YourBud, see [yourbud-market](https://github.com/cybex-dev/yourbud-market/blob/main/README.md) for more information on setting up this project.

### Getting Started: Client only:

1. #### Clone project:
    ```bash
    git clone https://github.com:cybex-dev/yourbud-mobile
    cd yourbud-market-client
    ```

2. #### Setup Environment

   This required [FlutterFire](https://firebase.google.com/docs/flutter/setup) (from npm's `firebase-tools`) to be installed and configured with the current project.

   Install & configure FlutterFire with:
    ```bash
    flutter pub global activate flutterfire_cli
    flutterfire configure
    ```

3. #### Install dependencies:
    ```bash
    flutter pub get
    ```

4. #### Build
   This builds to `build/web` directory.

    - Android (see documentation [here](https://flutter.dev/docs/deployment/android)):
    ```bash
    flutter build appbundle
    ```

   - iOS (see documentation [here](https://flutter.dev/docs/deployment/ios)
   ```bash
   flutter build ipa
   ```
5. ##### Deploy
    Deploy to PlayStore/AppStore using the generated `appbundle`/`ipa` file.
   