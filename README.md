# Argone One Driver for Fedora

This package will manage the fan and power buttons in the Argon One case on Raspberry Pi 4 and 5.

Please keep in mind that the Argon One v3 on Pi 5 requires a modded EEPROM, please see the official instructions.

Thanks to [Martin Wimpress for his Ubuntu Port](https://github.com/wimpysworld/argon1-ubuntu) and Argon 40 for pretty much everything else.

Notes to self

Daemon config goes in /etc/argon/daemon.conf

Poweroff script in /lib/systemd/system-shutdown/argond-poweroff

Power button script in /usr/local/bin/argond-btn

Fan goes in /lib/systemd/system/argond.service
