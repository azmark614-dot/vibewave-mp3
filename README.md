# VibeWave Android app

Native Android project for offline MP3 playback with a Media3 foreground media service.

## Included
- Choose audio files from the tablet with Android's file picker.
- Offline playback via Media3 ExoPlayer.
- Background playback service and system media notification/controls.
- Previous, play/pause and next controls.
- Audio focus handling and headphone-unplug pause support.

## Build an APK
1. Install Android Studio on a computer.
2. Extract this ZIP and open the `VibeWave-Android` folder (the one containing `settings.gradle.kts`).
3. Allow Gradle sync to download dependencies.
4. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. Install the generated debug APK on the Infinix XPad.

This environment has no Android SDK/Gradle build setup, so this download is project source, not a ready-to-install APK. It has not been built or device-tested here.

## If background playback is stopped
On the tablet, open Settings > Apps > VibeWave > Battery and choose Unrestricted / Don't optimize if that option is available. Allow notifications so playback controls can appear. Exact menu names vary by Android/XOS version.

The app plays audio files selected on the device. It does not download music from streaming services.
