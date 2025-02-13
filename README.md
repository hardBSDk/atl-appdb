# ATL AppDB

An unofficial app compatibility report for the [Android Translation Layer](https://gitlab.com/android_translation_layer/android_translation_layer) (ATL) project.

### What is ATL?

ATL is an compatiblity layer to run Android apps on Linux that convert the Android APIs to Linux APIs and convert the ARM code of apps to x86 to make them work on Intel/AMD CPUs, as it just does CPU emulation for apps it's faster than [Waydroid](https://waydro.id/) and other Android emulators.

### Why you created this catalog?

To use an emulator-like issue organization model.

### How to report an app?

Send a comment with your report in an existing issue or create an issue for your apps if it doesn't exist on the issues (please search before), they should contain the following information:

- App name
- App codename
- ATL version (commit hash) and installation method
- Details about possible issues that happen on the execution
- Screenshot (optional)

## How to install ATL?

You can install ATL from Flatpak or build from source:

### Flatpak

The Flatpak manifest can be found [here](https://github.com/flathub/io.gitlab.android_translation_layer.BaseApp)

- To install the Flatpak run the following command:

```
flatpak install io.gitlab.android_translation_layer.BaseApp
```

- To launch an app run the following command:

```
flatpak run io.gitlab.android_translation_layer.BaseApp path-to/your-apk
```

### Build from source

You can learn how to build ATL [here](https://gitlab.com/android_translation_layer/android_translation_layer/-/blob/master/doc/Build.md?ref_type=heads)
