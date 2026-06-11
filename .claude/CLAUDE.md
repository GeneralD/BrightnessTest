# BrightnessTest

Minimal legacy Android sample (circa 2017) demonstrating programmatic screen
brightness control on top of an unmodified "Basic Activity" template.

- Language/stack: Java, compileSdk 23, AGP 1.3.0, Support Library 23.1.0,
  minSdk 10 / targetSdk 23
- Status: legacy sample — will NOT build with modern Android Studio without
  migration (AndroidX, current AGP, JCenter removal)
- What it does: `MainActivity` sets system brightness to max via
  `Settings.System.putInt` (needs `WRITE_SETTINGS` permission) and window
  brightness via `WindowManager.LayoutParams.screenBrightness`
- Key paths: `app/src/main/java/com/zyxw/myapplication/MainActivity.java`,
  `app/src/main/AndroidManifest.xml`
