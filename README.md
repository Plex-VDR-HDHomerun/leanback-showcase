# Leanback Support Library Showcase App for Android TV

This sample app showcases different components that come with Leanback library.

The home screen in this sample app is a BrowseFragment consisting of a set of different cards.
Each card represents a component in Leanback.

All the cards in this sample app work except the Settings.
Settings for now crashes due to some internal issue, and we are working on
resolving that in the next few days.

We will also add a new music example card soon.
This will be a new PlaybackOverlayFragment that comes with a set of new
features.

## Introduction

- [Read more about Android TV introduction](http://www.android.com/tv/)
- [Android TV Developer Documentation](http://developer.android.com/tv)
- [Android TV apps in Google Play Store][store-apps]

## Dependencies

If you use Android Studio as recommended, the following dependencies will **automatically** be installed by Gradle.

- Android SDK v7 appcompat library
- Android SDK v17 leanback support library
- Android SDK v7 recyclerview library

## Getting Started

- Clone this repo:

```sh
git clone https://github.com/googlesamples/leanback-showcase.git
```

- Create a local.properties file if you haven't set ANDROID_HOME (You need to install Android SDK 'N').
- Open the project in [Android Studio][studio].
- Compile and deploy to your Android TV emulator or device (such as a Nexus Player).
- Open Live Channels [App][live] in your Android TV to add simulated TV channel service.


## Screenshots

![Screenshot](screenshots/Showcase-Snapshots.png)

Need more information about getting started with Android TV? Check the [official docs][getting-started].

## Support

If you need additional help, our community might be able to help.

- Android TV Google+ Community: [https://g.co/androidtvdev](https://g.co/androidtvdev)
- Stack Overflow: http://stackoverflow.com/questions/tagged/android-tv

## Contributing

We love contributions! :smile: Please follow the steps in the [CONTRIBUTING guide][contributing] to get started. If you found a bug, please file it [here][bugs].

## License

Licensed under the Apache 2.0 license. See the [LICENSE file][license] for details.

[store-apps]: https://play.google.com/store/apps/collection/promotion_3000e26_androidtv_apps_all
[studio]: https://developer.android.com/tools/studio/index.html
[getting-started]: https://developer.android.com/training/tv/start/start.html
[bugs]: https://github.com/googlesamples/androidtv-Leanback/issues/new
[contributing]: CONTRIBUTING.md
[license]: LICENSE
[live]: https://play.google.com/store/apps/details?id=com.google.android.tv&amp;hl=en