# Z370-ITX-AC-macOS
This is a working EFI/Clover configuration complete with config.plist and applicable kexts for macOS 10.13.3.

PC Part Picker build: https://pcpartpicker.com/b/8zFtt6

## System Specs
* ASRock Z370M-ITX/ac
* Intel i7-8700K 3.7GHz
* G.Skill Ripjaws V Series 16GB (2 x 8GB) DDR4-2400 Memory
* Crucial MX300 275GB M.2-2280 Solid State Drive
* Gigabyte GeForce GTX 1050Ti
* Corsair SF 450W 80+ Gold Certified Fully-Modular SFX Power Supply

## Post-install
* Audio install script: https://github.com/toleda/audio_CloverALC/blob/master/audio_cloverALC-130_v0.4.command
* NVIDIA web drivers: https://images.nvidia.com/mac/pkg/387/WebDriver-387.10.10.10.25.156.pkg
  * You may experience some minor lag with NVIDIA's latest drivers (*.156)
  * This was also a minor issue with *.104, however usability is still excellent.

## Working
* Displayport Dual 4k monitors
* APFS
* Sleep
* Audio
* FileVault

Bluetooth and WiFi do NOT work. You will need to get a compatible module for the
M.2 slot (and thus leaving it unavailable for an M.2 drive) or live without
Bluetooth and WiFi.
