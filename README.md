# Smart-Gauge-Mazda-2-Skyactiv
1. Download REDLINE Flasher

Download:

REDLINE-Flasher-windows.exe

Used to flash firmware to the ESP32-CYD device.

2. Download Firmware

Download:

SmartGauge-Mazda2Skyactiv.bin

Firmware file for SmartGauge Mazda2 Skyactiv.

Flashing Steps
Connect ESP32-CYD to your PC via USB.
Open REDLINE-Flasher-windows.exe.
Select the correct COM Port.
Select:
Panel: invert
Display: 80 MHz
Install: factory (first installation) or update (firmware update)
Click Browse and select:
SmartGauge-Mazda2Skyactiv.bin

Click Flash.
Wait for flashing to complete.
The device will restart automatically.
Recommended Settings

✅ First installation

Panel: invert
Display: 80 MHz
Install: factory

✅ Firmware update

Panel: invert
Display: 80 MHz
Install: update
Troubleshooting

Device not detected

Press Refresh.
Check USB cable.
Install CH340 driver.

Display colors incorrect

Go to:
SETUP → COLORS

Select the correct color profile.

Display glitches or tearing

Change Display from:
80 MHz → 40 MHz
