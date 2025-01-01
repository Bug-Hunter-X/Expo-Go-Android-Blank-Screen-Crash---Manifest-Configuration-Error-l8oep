# Expo Go Android Blank Screen/Crash: Manifest Configuration

This repository demonstrates a common issue in Expo Go Android development where an incorrectly configured `AndroidManifest.xml` file leads to a blank screen or immediate app crash upon launch.

**Problem:**
The `AndroidManifest.xml` file might be missing crucial activity declarations or intent filters needed for Expo Go to function correctly. This often happens when manually editing the manifest or when integrating third-party libraries with conflicting configurations.

**Solution:**
The provided `AndroidManifest.xml` file includes the necessary corrections.  Additionally, the `App.js` file provides a basic example of an Expo application to verify the fix.

**Steps to Reproduce:**
1. Clone this repository.
2. Run `expo start`.
3. Observe the blank screen or crash on your Android device (the initial `AndroidManifest.xml` demonstrates the error).
4. Review the corrected `AndroidManifest.xml` and re-run the application. It should now launch successfully.

**Key Considerations:**
* Always be cautious when manually modifying the `AndroidManifest.xml` file.  Consult the Expo documentation to understand the implications of changes.
* Use Expo's built-in functionalities whenever possible to avoid conflicts.
* When integrating third-party libraries, ensure their configurations are compatible with Expo.
