# How to install Android Studio in Ubuntu 22.04?

## Download installation package
https://developer.android.com/studio

## Install
1. Double click on downloaded `.tar.gz` file, then click `Extract`, keep the current directory to extract

![image](https://github.com/huongphamx/installation_note/assets/91840958/da16ea69-52fc-43da-b75a-80332dfc1c05)

2. After extracting, move the result extracted directory to `/usr/local` by following command (`sudo` is necessary). Here, I downloaded and extracted to `~/Downloads` 

```sh
cd ~/Downloads
sudo mv android-studio /usr/local
cd /usr/local/android-studio/bin
./studio.sh
```

3. A new installation window will be opened, keep installing.

## Add Android Studio icon to list applications
1. Create new project, choose any template and keep the default settings
2. After successfully creating new project, select `Tools > Create Desktop Entry > Create the entry for all users`

![image](https://github.com/huongphamx/installation_note/assets/91840958/ddf38ad5-fabd-4425-b59c-fbabbffccc49)

![image](https://github.com/huongphamx/installation_note/assets/91840958/a4e19761-9c8e-4fab-a948-11152e3efa5f)

## Enable KVM for supported hardware
TODO
