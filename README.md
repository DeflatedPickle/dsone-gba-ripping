# dsone-gba-ripping
A small tutorial on ripping GBA games with a DSone

## Backstory
I recently wanted to rip a GBA cartidge I found, for archival purposes, since I had never heard of it. Along with scanning it's box art and manual. This lead me down a rabbit hole mentioning all these extra things I also had never heard of. After looking around, I found some terms I could guess the meaning of and then it hit me, all these mentions of a "flashcart" just meant a DS cartridge with a microSD card slot. I've had a DSone sitting around in different places since I was around 11 but never knew what it was for or how to use it as it doesn't come with the needed software, and most links I could find nowadays were lost. So, 11-year-old me, here's a tutorial on something you can do with it

## Requirements
### Hard
- A DS/DS Lite
- A GBA cartridge
- A DSone cartridge
- A microSD card (of more than 4GB)
- A microSD card reader (microSD to SD, microSD to USB, etc)
### Soft
- An emulator (melonDS, DeSmuME, etc)

## Aquiring the Software
### [DSone Shell](http://eng.supercard.sc/manual/dsone/evolution/download.htm)
[**Download**](http://down.supercard.sc/download/DSone_SDHC_V3.0_sp8_eng.zip)
[**Backup**](https://archive.org/details/DSone_SDHC_V3.0_sp8_eng)

Since the DSone does not include the software it uses (it does come with a small CD but who has a disk player anymore?), we need to aquire the right files. It took me a little bit to find them since the official website leads to broken download links. Eventually, I found [this site](http://down.supercard.sc/download/) which seems to have new-ish versions. I chose to go with `DSone_SDHC_V3.0_sp8_eng`, not that I know the difference between that and the other files

Once you've downloaded the ZIP, plug your microSD card into the reader and plug the reader into your computer. Then extract the `MSFORSC.NDS` file and `scshell` folder to it. It's now ready to launch all your DS ROMS!

### [GBA Backup Tool](https://www.gamebrew.org/wiki/GBA_Backup_Tool)
[**Download**](https://projectpokemon.org/home/applications/core/interface/file/attachment.php?id=48516)
[**Backup**](https://archive.org/details/gba-backup-tool)

This is the program we'll use to extract our ROM to the microSD card. All we need from this folder is the `GBA_Backup_Tool.nds` file. Extract this to your microSD card alongside the `MSFORSC.NDS` file

## Getting the ROM
After putting the microSD card in the DSone catridge and the DSone catridge in your DS, put your GBA catridge in your DS. Turn the DS on. It should launch to the DSone shell. It might flicker a couple different colours but that's apparently ok. On the top screen, it should show the ROM for the GBA Backup Tool. Open it. Once it's found the ROM, you can press `A` to dump your save file but for the ROM, you'll need to press the right shoulder button to move to ROM dumping, press `A` and it should start dumping the ROM!

## Testing the ROM
Once the ROM has been fully dumped, take the microSD card out of the DSone and but it in the microSD card reader in your computer. You might need to unplug and replug it in. There should now be a folder relating to the GBA Backup Tool that'll contain your ROM and/or save file. Drag your ROM in to an emulator and make sure it starts
