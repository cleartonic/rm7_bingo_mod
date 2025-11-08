## RM7 Bingo Mod

Features:
- Immediate game start to stage select
- All 8 Robot Master, Intro, Museum and Wily stages selectable
- No intro cutscene when selecting intro stage
- Everything else untouched (dialogue & other cutscenes)
- Wily stage will give all Robot Master weapons, Rush Jet & Rush Search

Controls:
- Access intro stage: Hold L, select Wily
- Access museum stage: Hold R, select Wily

Most of the work was done by blueimp78 in their [RM7 practice hack](https://github.com/BlueImp78/RM7_Practice_Hack/tree/main), I just modified it slightly

# Usage
** UPDATE YOUR EMULATORS TO THE LATEST VERSION!! **  
Use Lunar IPS to apply rm7_bingo.ips to a Rockman 7 (J) ROM.  
It is recommended to make a copy of your source file, rename it something with "bingo" in the name, then apply the IPS patch to that file.  
** UPDATE YOUR EMULATORS TO THE LATEST VERSION!! **  

# Troubleshooting
If you want to confirm the before & after files are correct, do the following (on Windows):  
- Open Windows Explorer, navigate to the folder where your RM7 ROMs are  
- Shift + Right Click > "Open PowerShell window here"  
- In Powershell, use the following command, substituting the [file] with your file name: `CertUtil -hashfile '[file]' md5`  
- The source file should return the following hash: `e9c126cbd7c68c9e985dc501f625b030`  
- The patched file should return the following hash: `3a6ddcb586fb47429234f03527acfadc`  

Confirmed emulators: Snes9x 1.60+, bsnes, Bizhawk (SPECIFICALLY using the bsnes core! Config > Preferred Cores > Snes > BSNES, then Emulation > Reboot Core)