# Privacy Policy: Spatial Studio

**Last updated: October 29, 2026**

This policy covers the Android app **Spatial Studio** (package `com.mahfoozcc.spatialstudio`), an independent app for recording video and spatial audio with the Sony ECM-AX10 microphone.

## Summary

Spatial Studio does not collect, upload, sell or share any personal data. The app has no internet permission, so it cannot send anything off your phone. There are no accounts, no ads, no analytics and no crash reporting. Everything you record stays on your device unless you choose to share it.

## Information stored on your device

- **Recordings:** video and audio takes you record, plus their thumbnails and waveform previews. These are stored in the app's private storage.
- **Projects:** the video and multitrack audio projects you build from your takes.
- **Settings:** your capture and app preferences (resolution, frame rate, haptics and so on).
- **Exports:** files you export are saved to your phone's shared storage, in `Movies/Spatial Studio` or `Music/Spatial Studio`, where other apps like your gallery can see them.

None of this is uploaded anywhere by the app.

## Permissions and why we use them

- **Camera:** to record video. Only used while the capture screen is open. You can use audio-only mode without granting it.
- **Microphone:** to record audio from the ECM-AX10 or the phone's built-in mic, and to show live level meters and the wind warning. Required, since recording sound is the core of the app. Live audio is used only on-device for the meters; it is saved only when you press record.
- **USB access:** to connect to the ECM-AX10 microphone. Android asks for your permission when the mic is plugged in. The app reads audio and the mic's switch settings, and nothing else.
- **Notifications:** to show recording and export progress. Optional; recording and exporting still work without it.
- **Foreground service (microphone):** keeps a recording going if you switch apps or the screen turns off, with a visible notification.
- **Foreground service (data sync):** lets long exports finish in the background, with a visible notification.
- **Wake lock:** keeps the phone from sleeping during a recording or export.
- **Network state:** declared by Google's media playback library (Media3). Spatial Studio does not use the network.

You can revoke any permission at any time in Android Settings → Apps → Spatial Studio → Permissions.

## Network requests

None. The app does not request the internet permission and makes no network connections.

## Third-party services and SDKs

The app is built with open-source Android libraries from Google and JetBrains (AndroidX, Jetpack Compose, Media3, Kotlin). None of them collect or transmit data in this app. There are no analytics, advertising or tracking SDKs.

## Data shared with others

Spatial Studio shares nothing on its own. When you tap **Share** on an export, Android's share sheet hands the file to the app you pick (for example YouTube or a messaging app). That app's privacy policy then applies to the file.

## Backups

Android cloud backup is turned off for this app (`allowBackup="false"`), so recordings and projects are not copied to your Google account.

## Data retention and deletion

- Delete a take or project in the app to remove it immediately.
- Uninstalling the app, or Android Settings → Apps → Spatial Studio → Storage → Clear storage, removes all recordings, projects and settings stored inside the app.
- Exported files in `Movies/Spatial Studio` and `Music/Spatial Studio` are yours. They stay after uninstalling, and you can delete them with any file manager or gallery app.

The developer holds no copy of your data, so there is nothing to request deletion of.

## Security

All data stays on your device. Recordings, projects and settings are kept in the app's private storage, which other apps cannot read.

## Children's privacy

Spatial Studio is not directed at children under 13 and does not knowingly collect information from anyone.

## What we do NOT do

- No accounts or sign-in
- No ads
- No analytics, tracking or crash reporting
- No advertising ID or device identifiers collected
- No location access
- No internet access
- No selling or sharing of data

## Changes to this policy

If the app's handling of data changes, this page will be updated and the "Last updated" date changed. Significant changes will be noted in the app's release notes.

## Contact

Questions about this policy: **fullscreendev@gmail.com**, or open an issue in this repository.

---

Spatial Studio is an independent project. It is not affiliated with or endorsed by Sony. "Sony" and "ECM-AX10" are trademarks of Sony Group Corporation. Android, Google Play and YouTube are trademarks of Google LLC.
