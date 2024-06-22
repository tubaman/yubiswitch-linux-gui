# Yubikey Switcher GUI for Linux

This is a simple Yubikey switcher for Linux.  It's a single bash script that
puts an icon in the notification tray using `yad`.  The actual switching is done
with <https://github.com/insomniacslk/yubiswitch>


##  Installation

1. Install Yubiswitch CLI

Follow the instructions: <https://github.com/insomniacslk/yubiswitch> and make
sure it's in your path.

Allow sudo with no password for `yubiswith.py`.  In your sudoers file:

    myuser ALL=(ALL) NOPASSWD: /path/to/bin/yubiswitch.py

2. Install yad
```shell
apt install yad
```

3. Put `yubiswitchgui` script in your path

4. Set `yubiswitchgui` to run in your graphical session startup
