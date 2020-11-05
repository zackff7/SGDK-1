# SGDK 1.51 (april 2020)
## Copyright 2020 Stephane Dallongeville
Patreon: https://www.patreon.com/SGDK<br>
Github: https://github.com/Stephane-D/SGDK


**SGDK** is a free development kit allowing to develop software in **C language** for the **Sega Mega Drive**.
It contains the development library itself (with the code sources) and some custom tools used to compile resources.
SGDK uses the GCC compiler (m68k-elf target) and the libgcc to generate ROM image. Binaries (GCC 6.3) are provided for Windows OS for convenience but you need to install it by yourself for others operating systems.
Note that SGDK also requires Java (custom tools need it) so you need to have Java installed on your system.

SGDK library and custom tools are distributed under the MIT license (see [license.txt](license.txt) file).
GCC compiler and libgcc are under GNU license (GPL3) and any software build from it (as the SGDK library) is under the GCC runtime library exception license (see COPYING.RUNTIME file)
<br>
<br>
### GET STARTED

First, you need to know that SGDK uses C language (assembly is also possible but not necessary) so it's highly recommended to be familiar with C programming before trying to develop with SGDK. Learning C language at same time than learning 'Sega Mega Drive' programming is definitely too difficult and you will end nowhere. It's also important to have, at least, a basic knowledge about the Sega Mega Drive hardware (specifically the video system). If that's not the case then i recommend you to read these documents:
* Mega Cat Studios Sega Mega Drive graphics guide page: https://megacatstudios.com/blogs/retro-development/sega-genesis-mega-drive-vdp-graphics-guide-v1-2a-03-14-17
* Sik's Blog dedicated to assembly programming but explain a lot (and quite nicely) about the Sega Mega Drive hardware: https://plutiedev.com
* Genesis Software Manual which contains absolutely everything you need to know about the Sega Mega Drive: https://segaretro.org/images/a/a2/Genesis_Software_Manual.pdf

Then when you feel ready you can go further and finally install SGDK :)

You can find installation instructions and tutorials about how use SGDK on the wiki:
https://github.com/Stephane-D/SGDK/wiki

Also SGDK comes with a doxygen documentation (generated from .h header files) which provides complete information about SGDK structures and functions description. You can find it in the 'doc' folder: *doc/html/files.html*

Finally i also strongly suggest you to have a look on the available samples in the 'sample' directory of SGDK. The 'sprite' example is particularly useful as it show the basics in a small example.

You can also follow up-to-date and more complete online tutorials as this one (thanks to Ohsat for making them):
https://www.ohsat.com/tutorial/
You also have the great ones from Danibus (spanish only):
https://danibus.wordpress.com/
<br>
<br>
### HELP AND SUPPORT

If you need help or support with SGDK, you can go to the Spritesmind forum which is dedicated to Sega Mega Drive development and has a specific section for SGDK:
http://gendev.spritesmind.net/forum/

You can also join the SGDK Discord server to get support:
https://discord.gg/xmnBWQS
<br>
<br>
### MACOSX / LINUX

Unix/Linux users should give a try to the Gendev project from Kubilus:
https://github.com/kubilus1/gendev
It allows to quickly setup SGDK on a Unix environment.

MacOSX users also have access to SGDK with Gendev for MacOS from Sonic3D:
https://github.com/SONIC3D/gendev-macos

There is also the new and nice solution proposed by Daniel Valdivieso to use SGDK under any OS using Wine:
https://github.com/v4ld3r5/sgdk_vscode_template
<br>
<br>
### VISUAL STUDIO

You can find a Visual Studio template into the 'vstudio' folder to facilate SGDK integration with VS.
To go even further you can also install the VS extension made by zerasul:
https://marketplace.visualstudio.com/items?itemName=zerasul.genesis-code
<br>
<br>
### THANKS

- Chilly Willy for making almost all the JOY / controller support in SGDK (and the joy test sample ^^).
- Astrofa for the starfield donut sample ;)
- LIZARDRIVE for making the new SGDK logo.
- Kubilus for the Linux port of SGDK.
- Sonic3D for the OSX port of SGDK.
- Daniel Valdivieso for the SGDK multi-OS solution using Wine.
- Vladimir Kryvian for Visual Studio support and template.
- Tusario for resource manager tools.
- clbr for various contributions.
- jgyllinsky for providing / improving build batches.
- nolddor for fixes / contributions.
- starling13 for fixes.
- davidgf for contribution (replaced appack tool by apultra which is completely open).
- Banshaku for its contribution on improving makefile and deps generation with rescomp.
- Ohsat for making nice tutorials.
- ShiningBzh / Jeremy and Kentosama for their precious help in testing.
- Vetea and Studio Vetea Discord people in general for their support and kindness.
- all those i forgot and generally all people helping by providing support, reporting bugs and supporting SGDK in any way !
<br>
<br>
### SUPPORT SGDK

SGDK is completly free but you can support it on Patreon or using the Paypal donation link.

Patreon: https://www.patreon.com/SGDK<br>
Paypal donation link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=2SCWVXYDEEBUU

Thanks =) I wish you a great and happy coding time !
