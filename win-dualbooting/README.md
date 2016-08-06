#Windows Dual Boot settings

Some useful commands which may come handy when setting up a dualboot with windows 8/8.1 or 10

##Setting up new dual boot

`bcdedit /set {bootmgr} path \EFI\ubuntu\grubx64.efi`

1. change ubuntu with distro name
2. change x64 with your architecture

##Unsetting a dual boot

`bcdboot c:\windows`

#WARNING & Notes

**_CAUTIOUS THESE COMMANDS MODIFY YOUR BOOT SETTINGS! I'M NOT RESPONSIBLE IN ANY WAY IF YOU MISSUSE THESE!_**

_This is a free repo, if you find errors please report so I can improve. Free to share and use._
