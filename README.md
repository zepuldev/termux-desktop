**Cara menggunakan termux x11**

pertama-tama pkg update dan pkg upgrade dulu lalu ganti repo server dulu dengan

```text
termux-change-repo
```

lalu install package2 ini
```text
pkg install x11-repo
pkg install termux-x11-nightly
pkg install pulseaudio
pkg install xfce4
pkg install git
```

untuk menginstall chrome dan vscode
```text
pkg install code-oss
pkg install chromium
```

clone repo ini dengan git
```text
gt clone https://github.com/zepuldev/termux-desktop.git
```
masuk ke folder lalu ubah permission file startnya
```text
cd termux-desktop
chmod +x start
```
pindahkan file start ke home
```text
mv start $HOME/start
```
masuk ke ke home dulu lalu jalankan servernya dengan command startnya
```text
cd $HOME
./start
```
lalu buka termux x11nya dan tara selesai :)
