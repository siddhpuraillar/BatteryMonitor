# Privacy Policy — Battery Monitor

**Last updated:** April 15, 2026

This privacy policy explains how the **Battery Monitor** Android application ("the app", "we", "our") handles information. By installing and using the app, you agree to the practices described below.

## Summary

- The app runs **entirely on your device**.
- The app does **not** collect, transmit, or sell any personal data.
- The app does **not** use analytics, advertising, or tracking SDKs.
- The app does **not** require an account, login, or internet connection.

## Information the App Accesses

The app reads the following information **locally on your device** to provide its features. This data never leaves your device.

| Data | Why it's used | Where it's stored |
|------|---------------|-------------------|
| Battery level, temperature, voltage, charging status | Live dashboard, history graphs, alerts | On-device Room database |
| Charging and discharging sessions (start time, end time, start %, end %, plug type) | Session history and pattern analysis | On-device Room database |
| Installed apps and their battery usage stats | "App Battery Usage" screen | On-device; queried from the Android system at read time |
| User preferences (alarm thresholds, overlay style, color) | Remembering your settings | Android SharedPreferences (on-device) |

The app does **not** access your contacts, messages, photos, location, microphone audio, or any other personal content.

## Permissions the App Requests

| Permission | Purpose |
|-----------|---------|
| `POST_NOTIFICATIONS` | Show the persistent battery notification and alerts |
| `FOREGROUND_SERVICE` / `FOREGROUND_SERVICE_SPECIAL_USE` | Run the battery monitoring service reliably in the background |
| `RECEIVE_BOOT_COMPLETED` | Resume monitoring automatically after your phone reboots (if enabled in settings) |
| `USE_FULL_SCREEN_INTENT` | Display the optional Charge Screen overlay when charging begins |
| `PACKAGE_USAGE_STATS` | Compute per-app battery usage on the "App Battery Usage" screen |
| `QUERY_ALL_PACKAGES` | List installed apps alongside their battery usage |
| `CAMERA` | Optional: access the camera from the Charge Screen long-press shortcut |
| `FLASHLIGHT` | Optional: toggle the torch from the Charge Screen long-press shortcut |

All permissions are used only for the features listed above. No data gathered through any permission is sent off-device.

## Network Usage

The app does **not** make network requests. It does not include ads, analytics, crash-reporting, or remote-config SDKs.

## Data Sharing

We do **not** share, sell, rent, or disclose any data to third parties. There is no third party to share with, because the app collects nothing remotely.

## Data Retention and Deletion

- All data (battery records, session history, preferences) stays on your device.
- Uninstalling the app removes all of its data from your device.
- Android's "Clear storage" option in Settings → Apps → Battery Monitor also removes all data.

## Children's Privacy

The app does not knowingly collect information from children or anyone else. Because nothing is collected, the app is safe to use by all age groups.

## Security

Since no data leaves your device, there is no transmission for an attacker to intercept. On-device data is stored in Android's standard app-private storage, accessible only to the app itself (or to the device owner with root/ADB access).

## Changes to This Policy

If the app's behavior changes materially (for example, if a future version adds cloud sync), this policy will be updated and the "Last updated" date at the top will change. Continued use after an update means you accept the revised policy.

## Contact

Questions or concerns about this privacy policy:

**Email:** siddhpuraillar@gmail.com

---

*Battery Monitor is an independent project. This policy reflects the app's behavior as of the date above and applies to the version published under the package `io.battery.monitor`.*
