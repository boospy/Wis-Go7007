**You would like to show your appreciation for our help 8-o. Gladly. We thank you for your donation! ;)**

<a href="https://www.paypal.com/donate/?hosted_button_id=JTFYJYVH37MNE">
  <img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif">
</a>

# Wis-Go7007

<img src="https://raw.githubusercontent.com/boospy/Wis-Go7007/0622bc99f0e4adb10c9b23c765ed4d1f6a18c0d0/plextor.jpeg" width="" height="256">

## Getting started

This is an Proxmox VM Image with the ready to start Wis-Go7007 Software for the Plextor Videoconverter. 
Simply recover the vm on an Proxmoxserver or Proxmoxdesktop. Passthrough the Plextor Device and feel free to convert videos. 
Have a look at the "WatchMe" Movie for more Information. 

```
User: plextor
Password: plextor
```

## Important:
1. Do never update the system, it will breaks the wisgodrivers
2. Put in the USB Plextor Videoconverter after system has start successfully


Work with Plextor
--------------------------------------------------------------
It's easy to work with Plextor over SSH. Login with
```
ssh plextor@plextor.local -XY
```
Then you can use the commandlinetool "gorecord" (recommended)
Or the graphical tool "gogo-mini"

Use "halt" or "shutdown -h now" to turn of the system.


Have Fun!
