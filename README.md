# proud stories

Introducing "proud stories" - a micro social-investment SNS where users share their activities showcasing pride in their community with the world through short videos. Videos receive "applause" - a small monetary contribution for each upvote on your video. Check it out on the Play Store [here](loc cit).

This repo contains the mobile app written in React Native. Presently it is compatible with Android, but will be available on iOS in a future release.

## Getting Started

#### Installation

First install Android Studio, and Android SDK. To build the app, it will be necessary to add a file called `local.properties` in the `android/` folder containing the line `sdk.dir=path/to/Android/sdk`. The default paths are

```sdk.dir=/home/USERNAME/Android/Sdk``` (Linux) <br>
```sdk.dir=/Users/USERNAME/Library/Android/sdk``` (Mac) <br>
```sdk.dir=C:\\Users\\USERNAME\\AppData\\Local\\Android\\sdk``` (Windows)

Then from the root directory get dependencies with `npm install`.

#### Running the app in emulator with Android SDK

First open an emulator. Our primary device for testing was the Pixel 2, which can be started from terminal by running

```path/to/Android/sdk/emulator/emulator --avd Pixel_2_API_29 -no-snapshot -wipe-data```

Once the emulator has opened, from the root directory run `react-native run-android` to build the app and start metro bundler. If the server stops use `react-native start` to restart without the rebuild.
