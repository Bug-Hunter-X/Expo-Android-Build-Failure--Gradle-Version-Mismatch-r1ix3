# Expo Android Build Failure: Gradle Version Mismatch

This repository demonstrates a common error encountered when building Android APKs using Expo CLI. The error arises from a mismatch in the required and available Gradle versions.

## Problem
The Android build process depends on a specific version of Gradle. If the incorrect version is used, the build fails, resulting in error messages similar to `Could not resolve all artifacts for configuration ':app:classpath'. > Could not download gradle-7.5.1-all.zip`.

## Solution
The solution involves explicitly specifying the correct Gradle version in the `build.gradle` file.

## Setup
1. Clone this repository.
2. Navigate to the directory.
3. Run `npm install` to install project dependencies.
4. Attempt to build the project using Expo CLI. You'll encounter the Gradle error. 
5. Replace `build.gradle` with `build.gradle.fixed` and try building again.