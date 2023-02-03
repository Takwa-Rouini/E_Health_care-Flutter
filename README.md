# flutter_application_2

A new Flutter project.

## Getting Started
# Get the Flutter SDK
Download the following installation bundle to get the latest stable release of the Flutter SDK:
https://storage.googleapis.com/flutter_infra_release/releases/stable/windows/flutter_windows_3.7.1-stable.zip
# Update your path 
add Flutter to the PATH environment variable:
# Run flutter doctor
C:\src\flutter>flutter doctor
This command checks your environment and displays a report of the status of your Flutter installation.
# Install Android Studio

1/ Download and install Android Studio. \n
2/ Start Android Studio, and go through the ‘Android Studio Setup Wizard’. This installs the latest Android SDK, Android SDK Command-line Tools, and Android SDK Build-Tools, which are required by Flutter when developing for Android. \n
3/ Run flutter doctor to confirm that Flutter has located your installation of Android Studio. If Flutter cannot locate it, run flutter config --android-studio-dir <directory> to set the directory that Android Studio is installed to.
# Set up the Android emulator
To prepare to run and test your Flutter app on the Android emulator, follow these steps:

Enable VM acceleration on your machine.\n
Launch Android Studio, click the AVD Manager icon, and select Create Virtual Device… \n
In older versions of Android Studio, you should instead launch Android Studio > Tools > Android > AVD Manager and select Create Virtual Device…. (The Android submenu is only present when inside an Android project.)
If you do not have a project open, you can choose Configure > AVD Manager and select Create Virtual Device…
Choose a device definition and select Next.
Select one or more system images for the Android versions you want to emulate, and select Next. An x86 or x86_64 image is recommended.
Under Emulated Performance, select Hardware - GLES 2.0 to enable hardware acceleration.
Verify the AVD configuration is correct, and select Finish.
In Android Virtual Device Manager, click Run in the toolbar. The emulator starts up and displays the default canvas for your selected OS version and device.

# Agree to Android Licenses
1/ Make sure that you have a version of Java 8 installed and that your JAVA_HOME environment variable is set to the JDK’s folder.
2/ Run the command : 
flutter doctor --android-licenses
3/ run flutter doctor again to confirm that you are ready to use Flutter.



This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
