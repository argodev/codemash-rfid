# Digital Signage

This is a collection of notes developed to track our work on digital signs used throughout the conference.

As our screens are powered via Raspberry Pis, turning them into kiosk mode and launching the browser automatically
on boot is quite helpful.

One site that was beneficial is [Gordon Turner's blog](https://blog.gordonturner.com/2017/12/10/raspberry-pi-full-screen-browser-raspbian-december-2017/).

Steps Taken:

1. Install some fonts and basic utilities
1. Modify `.config/lxsession/LXDE-pi/autostart`
1. Reboot (all is mostly set now)
1. Install `xdotool` utility
1. Configure `~/screen-control.sh` which allows the user to turn on/off the screen

NOTE: To get out of Kiosk Mode in Chrome you type `shift control q`
