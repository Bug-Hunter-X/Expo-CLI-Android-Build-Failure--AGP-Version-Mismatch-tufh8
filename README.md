# Expo CLI Android Build Failure: AGP Version Mismatch

This repository demonstrates a common issue encountered when building Android APKs using the Expo CLI.  The problem arises from a version conflict between the Android Gradle Plugin (AGP) required by Expo and the version installed in the Android development environment.

The `android_build_error.js` file showcases a project setup that triggers this error.  The solution is provided in `android_build_solution.js`, outlining steps to resolve the AGP version incompatibility.

## Reproducing the Error

1. Clone this repository.
2. Navigate to the project directory.
3. Attempt to build an Android APK using `expo build:android`.  The build process will fail with an AGP version mismatch error.

## Solution

The solution involves ensuring the correct AGP version is installed and configured.  Consult the official Expo documentation and Android developer guides for detailed instructions on managing AGP versions and resolving compatibility issues.  The `android_build_solution.js` provides potential approaches that you can adapt.

## Note

The specific AGP version causing the conflict may vary depending on the Expo SDK version and the Android SDK tools installed on your system.  Always refer to the most up-to-date Expo documentation for the appropriate AGP version.