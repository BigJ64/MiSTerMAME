# MiSTerMAME
The purpose of this Script to to aid in downloading the correct MAME ROM Zips to use for the new MiSTer Arcade Core MRA configuration. This Script is for testing/educational purposes only.

# Updater Script and INI Download

<a href="https://retrodriven-nextcloud.cloud.seedboxes.cc/s/Updater/download"> Script Updater and INI File Download </a>

## Usage ##
* Download the ZIP file above and Extract/Copy <b>Update_RetroDriven_MAME.sh</b>, <b>Update_RetroDriven_MAME.ini</b>, and <b>Cache_Remover_RetroDriven.sh</b> to your Scripts Folder on your MiSTer SD Card(typically /media/fat/Scripts).
* Simply run <b>Update_RetroDriven_MAME.sh</b> via MiSTer Scripts Menu to Download/Update your MAME ROM Zips/MRAs and Unofficial Arcade Cores(RBF Files).
* Optional: Changing the <b>Update_RetroDriven_MAME.ini</b> file is optional based on your setup/needs.
* Optional: If you run into any issues downloading the MAME/MRA/HBMAME Zip files you can clear the Cache by running the <b>Cache_Remover_RetroDriven.sh</b> Script. After you do this please run the Updater Script again.

## New MRA Arcade Core Folder Structure ##
The following below is the directory structure for the new MRA/Mame Arcade Core setup: 

* /_Arcade/*.mra
* /_Arcade/cores/*.rbf
* /_Arcade/mame/*.zip 
* /_Arcade/hbmame/*.zip

You can place your Mame/HbMame Zip files into your Games folder instead like below: 
* /Games/mame/*.zip
* /Games/hbmame/*.zip

## Unofficial Arcade Core/RBF Downloads ##
As of v2.0 of this Script, I have included the ability to Download/Update Unofficial Arcade Core RBF files.

* Jotego's Public Cores will be Download/Updated just like his Updater Script is doing currently. NOTE: His Beta Cores are not included as those are for his Patreon Subscribers only.
* All other Unofficial Arcade Cores are ones that I've come across that are not currently a part of the Official MiSTer GitHub.
* If/When these Unofficial Arcade Cores are added to the Official MiSTer GitHub, they will be removed on my end to avoid duplicates/issues.
* Be sure to set the INI Option "REMOVE_ARCADE_PREFIX" based on your current Arcade Core set up to avoid duplicates/issues. 
* If you do not wish to Download the Unofficial Arcade Core RBF files set "RBF_DOWNLOAD" to False in the INI File.

## Credits ##
* <a href="https://github.com/MiSTer-devel/Main_MiSTer/wiki">Sorgelig</a>
* <a href="https://github.com/nullobject">Nullobject</a>
* <a href="https://github.com/jotego">Jotego</a>
* <a href="https://github.com/gaz68">gaz68</a>
* <a href="https://github.com/alanswx">alanswx</a>
* <a href="https://github.com/MrX-8B">MiSTer-X</a>
* <a href="https://github.com/MiSTer-devel/MRA-Alternatives_MiSTer">eubrunosilva</a>

## Notes ##
* You can save Mame and HBMame files within the "Games" Folder on your MiSTer SD Card. By default this Script saves these files within /_Arcade/Mame and /_Arcade/hbmame but the Path's can be change to your liking via the INI File.
* Unofficial MRA files will be removed as Arcade Cores become Official within MiSTer Github and Official Downloader Script. These files within the _Unofficial Folder should be removed/cleaned up automatically but in the event that this does not take place you are free to delete the MRA files manually if needed. 

## Disclaimer / Legal Information
By downloading and using this Script you are agreeing to the following:

* You are responsible for checking your local laws regarding the use of the ROMs that this Script downloads.
* You are authorized/licensed to own/use the ROMs associated with this Script.
* You will not distribute any of these files without the appropriate permissions.
* You own the original Arcade PCB for each ROM file that you download.
* I take no responsibility for any data loss or anything, use the script at your own risk.
