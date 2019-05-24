# CaesarIII-RPI
Caesar III for Raspberry Pi based on Julius source port

**Caesar III - Julius source port**

Due to Julius source port, Caesar III can now be built and run on our Raspberry Pi with the source port called "Julius". This port relies on SDL2 libs and is working in RetroPie.
![JazzJackrabbit-RPI](https://raw.githubusercontent.com/tpo1990/JazzJackrabbit-RPI/master/Screenshots/2019-01-21-135654_1280x720_scrot.png)

The game is fully playable.
The script provides an automatic installation and uninstallation for compiling and building on Raspberry Pi and RetroPie.

Install time: 5-10 minutes

**Build process:**
1: Download and install necessary required libs for SDL and etc.
2: Create folder openjazz or clone from github.
3: Compile/install openjazz source port
4: Download Jazz Jackrabbit Shareware and extract into root of openjazz folder.
5: Create shortcut on Raspbian desktop or create JazzJackrabbit.sh file into Ports folder in RetroPie.

**In order to play:**
Add all data files from your Caesar 3 installation folder to /home/pi/RetroPie/roms/ports/caesar3. This could be from the GOG version.

**Notes:**
This build works great. I have not see any bugs yet.

**Disclaimer:**
This installation script is provided as is. Im not responsible for anything happening with your Raspberry Pi including corruption of SD card, Hardware damage. For support and help you can contact me here on RetroPie forums.
