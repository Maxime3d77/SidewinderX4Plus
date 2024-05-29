# SidewinderX4Plus


![banniere](/img/Artillery-Sidewinder-X4-Plus-specs.jpg)

# Update


https://drive.google.com/file/d/107kTrNO3BHI6ApPVBxDuyktZrRhjazqV/view?usp=sharing


![MAJ](/img/X4MAJ001.png)

Insert the USB drive with the firmware. 
Click on "Tools" — "About" — "Renewable system" to start the automatic update

# Profile Orcaslicer


I provide you with my Orcaslicer profile for your Sidewinder X4 Plus

[Profile Sidewinder X4 plus](/Orcaslicer/Sidewinder%20X4%20PLUS.orca_printer)

The screen can freeze and the image is not supported by artillery with this slicer.

Prints exemple:

# Profile Klipper / Webcam

## Printer.cfg

You can download my printer.cfg
Please note that you have to redo all the Z-offset, leveling etc...

X4 Pro: https://drive.google.com/file/d/1uTOqfRErMxihiJ_Vys_JdO44f94fX6zy/view

X4 Plus: https://drive.google.com/file/d/1LoE4GLe6Z-E5a2HSxtbjLrdTVquUn6mr/view

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

## EMMC

X4 Pro Image file: https://drive.google.com/file/d/1uTOqfRErMxihiJ_Vys_JdO44f94fX6zy/view

X4 Plus Image file: https://drive.google.com/file/d/1uTOqfRErMxihiJ_Vys_JdO44f94fX6zy/view

You will need an emmc usb adapter: https://fr.aliexpress.com/item/1005006279363979.html?spm=a2g0o.order_list.order_list_main.5.159c5e5bx7BVWI&gatewayAdapt=glo2fra

You will need the etcher software: https://etcher.balena.io/

Remove the sidewinder cover and recover the EMMC by removing the 2 screws. 

![SidewinderX4](/img/Sidewinderx4EMMC.png)

Plug it into the EMMC adapter and connect it to your computer. 

![SidewinderX4](/img/Sidewinderx4EMMC2.png)

Using the etcher software, attach the EMMC to your printer's system.