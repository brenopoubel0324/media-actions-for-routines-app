# Media Actions for Routines

Skip a track, pause a podcast, or adjust media volume without opening your player. Put playback controls in a Samsung Routine or keep them on your Android home screen in a widget you can resize and style.

**[Download the phone APK](https://github.com/brenopoubel0324/media-actions-for-routines-app/releases/download/v0.36/media-actions-phone-0.36.apk)** · **Stable 0.36** · Android 13 or later

[SHA-256 checksum](https://github.com/brenopoubel0324/media-actions-for-routines-app/releases/download/v0.36/SHA256SUMS.txt) · [Release notes](https://github.com/brenopoubel0324/media-actions-for-routines-app/releases/tag/v0.36)

<img src="images/playback-widget.png" alt="Three playback icon styles shown at compact, wide, and full-width spacing" width="720">

*Android-rendered preview from an earlier build, showing icon styles and spacing. The background is illustrative.*

## Get started

1. Download `media-actions-phone-0.36.apk` from [Releases](https://github.com/brenopoubel0324/media-actions-for-routines-app/releases). If you already use the original **Media Actions** app, install the update over it to keep your settings and widgets. Follow the [migration steps](https://github.com/brenopoubel0324/media-actions-for-routines-app/releases/tag/v0.36#install-or-update) if you need to move settings from the separate Preview app.
2. Open Media Actions, allow **Notification access** for playback controls, start a media player, and try the test buttons. Android may ask you to allow restricted settings for a sideloaded app.
3. Open Samsung **Modes and Routines** and choose **Open an app or do an app action → Media Actions**. Pick **Previous**, **Play/Pause**, or **Next**. To use a widget instead, add one from your launcher’s widget picker.

Samsung Routines, Routines+ gestures, and LockStar widget placement depend on your device and One UI version. Playback needs a local media session that exposes the requested action. Remote playback such as Spotify Connect may not expose one.

## Make the widget your own

- **Media controls** puts Previous, Play/Pause, and Next in one widget.
- **Media volume** adjusts local volume without Notification access or an active media session.
- **Playback and volume** gives you volume down, Play/Pause, and volume up in one place.

Open **Edit existing widget** to set the layout, spacing, borders, or colors for each widget. Version 0.36 adds filled buttons, a capsule background, and separate colors for the widget, the controls, and Play/Pause. Existing widgets keep their saved look. If LockStar offers no edit action, use the editor in Media Actions.

<details>
<summary>See the widget editor</summary>

<img src="images/widget-editor.png" alt="Widget editor showing icon size, exact spacing, a playback preview, and save controls" width="320">

*Test-environment capture from an earlier build. The editor layout has since changed.*

</details>

## Wear OS

The optional [Wear OS companion (0.9 experimental)](https://github.com/brenopoubel0324/media-actions-for-routines-app/releases/tag/wear-v0.9-experimental) exposes Previous, Play/Pause, and Next as entries you can choose in **Wear Button Remapper**. Install the companion on the watch and use the stable APK on the phone. Physical button bindings and playback on the watch still need validation on the Galaxy Watch8 test firmware.

## Privacy and support

Playback controls use Android’s Notification access to reach media sessions. Media Actions does not read or store notification content. Phone widgets and routines act locally. The optional watch companion uses Google Play services Data Layer, which can use Bluetooth or Google's network infrastructure.

[Report a problem](https://github.com/brenopoubel0324/media-actions-for-routines-app/issues/new) with your app version, device model, Android or One UI version, and whether it happened in a routine, widget, or watch shortcut. Leave out personal notification content, account information, and device identifiers.

[Third-party notices](THIRD_PARTY_NOTICES.md)
