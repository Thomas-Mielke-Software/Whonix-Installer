# Whonix-Installer
a Windows installer for the Whonix virtual machines

HOWTO:
1.  Put Whonix .ova files and Virtual Box installer in your Whonix-Installer folder.
2.  Download InnoSetup from http://www.jrsoftware.org/isdl.php#stable and install it.
3.  Open the .iss file with InnoSetup and compile.
4.  Use 7zip to create a .7z archive with the .ova files, the VirtualBox installer, and the Whonix-WinSetup-##.#.#.#.#.exe. Make sure to set compression level to ultra.
5.  Download 7zip SFX Maker from http://sourceforge.net/projects/sfx-maker and extract it to your Whonix-Installer folder.
6.  Open the config file 7-Zip SFX Maker\Config\7z-SFX-Maker-Config-for-Whonix-Installer.xml with 7zip SFX Maker.
7.  Drag your .7z file to the files box of the 7zip SFX Maker and press the 'Make SFX' button.
8.  Your self-extracting archive Whonix-Installer.sfx.exe is ready to be released.
