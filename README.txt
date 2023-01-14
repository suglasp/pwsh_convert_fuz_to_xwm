
*.fuz to *.xwm sound converter
-------------------------------

Used for the Fallout sfx conversion kit. See project https://github.com/suglasp/fallout4_fallout76_sfx_conversionkit .

A powershell script that can read a folder with fuz data files from Skyrim or Fallout,
and extract in bulk the xwm data from all fuz files present in the folder.
The fuz files of xwm files, are processed natively in Powershell.
No 3rd party tools needed.

Setup:
Download convert_fuz_to_xwm.ps1 to a folder.

Usage:
Start Powershell (works in Powershell 7 to on Windows).
Run .\convert_fuz_to_xwm.ps1 -CustomDir <path_to_target_folder>

If a .fuz file is seen, it will extract the xwm data to a xwm file and place the new file next to the fuz file.
In case a xwm file with the same name as the fuz file exists, the script will skip the file and notify you.

Pieter a.k.a. Suglasp
