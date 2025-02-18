# X-Signer

- X-Signer is a lightweight Android app designed for signing APK/AAB files with various signature schemes (v1, v2, v3, v4). It provides an easy-to-use interface to help users securely sign their apps without hassle.

## Features

- Supports signing APKs and AABs with multiple signature versions (v1, v2, v3, v4).

- Option to enable both v1 + v2 signatures or all signature versions (v1, v2, v3, v4).

- Local storage for device data without cloud integration.

- Encrypts all locally stored data for security. (Well not implemented yet :3)

- Only some basic device informations are collected (e.g., model, Android version, brand), but no personal data is ever collected.

- Uses Google Firebase solely for update checks.


## How to Use

1. Install the App
Download and install the APK on your Android device.

2. Grant Runtime permissions
Grant the all files access to the app in order to work with files in your device storage.


2. Select the APK/AAB file
Choose the APK or AAB file you want to sign or pick an app from your installed apps.


3. Select Signature Versions
Choose the desired signature versions (v1, v2, v3, v4) from the pre-sign dialog.


4. Sign the APK/AAB
Tap the 'Sign' button to sign your file. a snackbar popup will show the signed file path.



## Permissions

- Storage Access: Required for reading and saving APK/AAB files.

- Internet Access: Used only for checking app updates via Google Firebase.

- Installed packages list access : Used to fetch installed apps lists to extract the APK file from the selected app for signing.


## Privacy

- The app does not collect or share any personal data.

- All data is stored locally and encrypted for security.


## License

This project is licensed under the custom License - see the [LICENSE](https://github.com/Yamenher/X-Signer/blob/nightly/LICENSE) file for details.