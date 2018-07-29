# Digital Signage

This is a collection of notes developed to track our work on digital signs used throughout the conference.

As our screens are powered via Raspberry Pis, turning them into kiosk mode and launching the browser automatically
on boot is quite helpful.

One site that was largely beneficial is [Gordon Turner's blog](https://blog.gordonturner.com/2017/12/10/raspberry-pi-full-screen-browser-raspbian-december-2017/). 

> It should be noted that the instructions below are only slight modifications from Gordon's post and any credit should be directed his way. I am providing it here only as a means of documenting what we did.

## General Process

### Install some fonts and basic utilities that we will need

```bash
sudo apt-get install -y ttf-mscorefonts-installer unclutter x11-xserver-utils xodotool vim -y
```

### Modify the autostart script

used `scp` to copy/overwrite autostart on each machine

```bash
scp autostart pi@cm001:~/.config/lxsession/LXDE-pi/
```

### Reboot (all is mostly set now)

### Configure `~/screen-control.sh` which allows the user to turn on/off the screen

used `scp` to copy screen-control.sh to each machine

```bash
scp screen-control.sh pi@cm001:~/
```

NOTE: To get out of Kiosk Mode in Chrome you type `shift control q`
