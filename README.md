# move-to-previous-monitor

Script to move windows from one monitor to the next in Xubuntu

Even though I don't use Xubuntu anymore, people are still interested
in this script. Sweet! Glad it can help others.

I mapped `ctrl+alt+n` to exectute this script.

## Usage

```
wget https://github.com/xavierbaez/move-to-previous-monitor/raw/master/move-to-previous-monitor
chmod +x move-to-previous-monitor
mv move-to-previous-monitor /somewhere/in/your/$PATH
```

## Dependencies

```
# Xubuntu 18.04
sudo apt install xdotool wmctrl

# Xubuntu 16.04
sudo apt-get install xdotool

# Arch based (Manjaro / Endeavour OS)
sudo pacman -S xorg-xwininfo
sudo pacman -S xdotool
sudo pacman -S wmctrl
```

## Code of Conduct

[We have one](code_of_conduct.md), and you're expected to follow it.

## Support

Since I don't use Xubuntu and therefore don't have a way to test changes, I'm going to rely on others to QA and give me feedback.

## Thanks

* [icyrock](http://icyrock.com/blog/2012/05/xubuntu-moving-windows-between-monitors/) post for initial development
* [@jordansissel](https://github.com/jordansissel) for his excellent [xdotool](https://github.com/jordansissel/xdotool)
