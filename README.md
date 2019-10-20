# Flutter Europe conference app

[![Codemagic build status](https://api.codemagic.io/apps/5da4ce9b9f20ef349b12739c/5da4ce9b9f20ef349b12739b/status_badge.svg)](https://codemagic.io/apps/5da4ce9b9f20ef349b12739c/5da4ce9b9f20ef349b12739b/latest_build)

This is repository of [Flutter Europe](https://fluttereurope.dev/) official conference app.

![App Logo](docs/logo.png)

## Getting Started

For now this app is a simple Flutter app that should run on any device that Flutter supports.

### Running and building

This project is based on 3 flavors: `dev`, `tst` and `prod`. In order to run given flavor in VS Code you should define custom `launch.json` file.

You need to provide your Google Services configuration files for iOS and Android.

Project also contains custom `fastlane` configuration for Android and iOS. In case of iOS configuration it's able to set provisioning profiles, archive and deploy app to Firebase App Distribution or Testflight. In case of Android it's used only to distribute app to Firebase App Distribution and Google Play.

## Contributing

If you want to contribute, please contact us directly. We hope to publish some contribution policy soon.
