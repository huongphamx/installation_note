This note is for installation flutter on Ubuntu 22.10, it's may work with Ubuntu 22.04 or newer.
To install Flutter, you need to install Java, and also Android Studio
* To install Java, follow this [instruction](https://www.digitalocean.com/community/tutorials/how-to-install-java-with-apt-on-ubuntu-22-04)
* To install Android Studio, first download the [zip package](https://developer.android.com/studio), 
and then follow the [instruction](https://developer.android.com/studio/install#linux) of Google. 
Aslo note that you need to install the [required libraries](https://developer.android.com/studio/install#64bit-libs). 
With android studio, you also need to install Android SDK command-line tools by create a blank project, then in the toolbar menu, select Tools > SDK Manager > SDK Tools
then check the proper SDK.

Follow the instruction in [Flutter site](https://docs.flutter.dev/get-started/install/linux):
- first, get the Flutter SDK, I prefer using snapd to install:
sudo snap install flutter --classic
To confirm if installation success, run
flutter sdk-path
- Then, you need to agree with android licenses, by running
flutter doctor --android-licenses
read the licenses, and allow each of them by pressing Y.
