# UVK5_reversing
Reverse engineered UV-K5 schematics
These are extremely incomplete and inaccurate schematics me and others have made for Quansheng UV-K5 radio.

All seen here is based on looking and measuring the radio PCB. 

These files are here mostly for my own convenience and to make it possible for others to complain about inaccuracies.

This does not have a corressponding PCB yet, because I did not care for it.

##### Contributing
If you want to reverse some segment of the PCB:
- Join and ask questions in the **[UV-5K Dev Telegram group]([https://eff.org](https://t.me/quansheng_uvk5_en))**. 
- Check if a sheet for the subsection already exists.
- Add a new sub sheet to the top level schematic sheet for your segment.
- Name it, use no spaces.
- Annotate your schematic with "First free after sheet number X 100"-option in Kicad.
- Pullrequest that file or whatever. 

##### Links to firmwares and more info
Tunas1337 hosts a good bunch of modded firmwares.
<https://github.com/Tunas1337/UV-K5-Modded-Firmwares>
Also the awesome uvmod-kitchen, which allows one can pick & mix your mods to get a custom firmware image.
<https://github.com/amnemonic/Quansheng_UV-K5_Firmware/tree/main/uvmod_kitchen>
Amnemonic's collection of stock firmware images has helped with the reversing process.
<https://github.com/amnemonic/Quansheng_UV-K5_Firmware>
You can read those firmware images with fagci's firmware decoder tool
<https://github.com/fagci/qs-uvk5-firmware-modder>
