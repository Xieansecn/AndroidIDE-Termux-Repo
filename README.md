# [AndroidIDE](https://github.com/AndroidIDEOfficial/AndroidIDE) Termux Repo for Snapshot

## How to use?

### 1. Unzip to path

Open your terminal app in phone.(such as: MT Manager, Termux, etc.)
```
tar -zxvf mirror_arm64.tar.gz -C /storage/emulated/0/androidide-repo
```
### 2. Into AndroidIDE Terminal
```
nano /data/data/com.itsaky.androidide/files/usr/etc/apt/sources.list
```
Clear or comment out the content.
```
deb [trusted=yes] file:///storage/emulated/0/androidide-repo stable main
```
Need `trusted=yes` for pass outdated GPG key signing.
