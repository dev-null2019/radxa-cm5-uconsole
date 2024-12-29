# radxa-cm5-uconsole
Radxa CM5 in the Clockworkpi uConsole. 
</br>
</br>
What does work:</br>
-Display</br>
-Keyboard</br>
-USB</br>
-Power management</br>
-4G module</br>
-microSD card</br>
</br>
What doesnt work, and will never work:</br>
-Internal Wifi/Bt (the Radxa CM5 has no Wifi/Bt on board)</br>
</br>
What does work with Hardware modifications:</br>
-HDMI out</br>
</br>
What does maybe work:</br>
-Audio (mono only)</br>
</br>
</br>
Currently you need to flash the "Radxa CM5 Lite on RPI CM4 IO Image" (https://github.com/radxa-build/radxa-cm5-rpi-cm4-io/releases/download/rsdk-b3/radxa-cm5-rpi-cm4-io_bookworm_cli_b3.output.img.xz) on a microSD and put the CM5 into a Rpi CM4 IO board. 
</br></br>
Boot it up, install my kernel and apply the devicetree overlays with rsetup. Then put the CM5 back into your uConsole.
</br></br>
I will try to build an image based on the Radxa CLI Image so you can put the CM5 directly into the uConsole without IO Board ...
