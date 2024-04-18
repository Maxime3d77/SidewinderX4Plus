# SidewinderX4Plus


![banniere](/img/Artillery-Sidewinder-X4-Plus-specs.jpg)


# Profile Orcaslicer


I provide you with my Orcaslicer profile for your Sidewinder X4 Plus

[Profile Sidewinder X4 plus](/Orcaslicer/Sidewinder%20X4%20PLUS.orca_printer)

Prints exemple:

# Profile Klipper / Webcam

## Printer.cfg

You can download my printer.cfg
Please note that you have to redo all the Z-offset, leveling etc...

[Profile Klipper](/Klipper/printer.cfg)

## Webcam

To add a webcam, you can use my configuration file.

You'll also need to connect to the printer via ssh.

user: mks

password: makerbase

execute the following commands:

```
sudo systemctl enable webcamd.service
sudo systemctl start webcamd.service
```

Also activate the camera in Fluiid

![REnableCam](/img/camfluiid.png)

## ADXL

Coming Soon
