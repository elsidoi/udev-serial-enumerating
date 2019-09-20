# udev-serial-enumerating
Udev rule to create enumerated symlinks for connected serial devices.
When device is connected it has USB path unique for every USB port on machine (path may be not so static when using external USB hubs). So according to path you can create enumerated or named symlinks to created tty devices.
For example you can name any ACM device connected to front USB socket as /dev/ttyFrontUSB instead of /dev/ttyUSBN where N depends on number of ACM devices connected to PC.
