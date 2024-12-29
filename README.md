# radxa-cm5-uconsole
Radxa CM5 in the Clockworkpi uConsole. 


What does work:
-Display
-Keyboard
-USB
-Power management
-4G module
-microSD card

What doesnt work, and will never work:
-Internal Wifi/Bt (the Radxa CM5 has no Wifi/Bt on board)

What does work with Hardware modifications:
-HDMI out

What does maybe work:
-Audio (mono only)


Currently you need to flash the Radxa CM5 Lite on RPI CM4 IO Image (https://github.com/radxa-build/radxa-cm5-rpi-cm4-io/releases/download/rsdk-b3/radxa-cm5-rpi-cm4-io_bookworm_cli_b3.output.img.xz) and put the CM5 into a Rpi CM4 IO board. Boot it up, install my kernel and apply the devicetree overlays with rsetup. Then put the CM5 back into your uConsole.
I will try to build an image based on the Radxa CLI Image so you can put the CM5 directly into the uConsole without IO Board ...
