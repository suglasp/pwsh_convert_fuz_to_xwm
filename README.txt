
*.fuz to *.xwm sound converter
-------------------------------

Used for the Fallout sfx conversion kit. See project https://github.com/suglasp/fallout4_fallout76_sfx_conversionkit .

This is a wrapper script that uses BmlFuzDecode behind the scenes to convert in bulk fuz files to xwm.
You can target a folder, and the scripts will convert any fuz file (also in subfolders) to xwm.

Setup:
Download convert_fuz_to_xwm.ps1 to a folder.
create a subfolder (in the same root folder where you put convert_fuz_to_xwm.ps1) with the name "fuze".
Download BmlFuzTools utilities from ttps://www.nexusmods.com/skyrim/mods/73100/ (download BmlFuzTools and extract the zip file. Copy *.exe files to "fuze" folder).

Usage:
Start Powershell (works in Powershell 7 to on Windows).
Run .\convert_fuz_to_xwm.ps1 -CustomDir <path_to_target_folder>

If a .fuz file is seen, it will convert it to xwm and place the new file next to the fuz file.
In case a xwm file with the same name as the fuz file exists, the script will skip the file and notify you.

Pieter a.k.a. Suglasp
