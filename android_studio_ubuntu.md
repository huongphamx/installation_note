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

## Enable KVM for supported hardware
TODO
