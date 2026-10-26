🚗 REDLINE Flasher — SmartGauge Mazda2 Skyactiv

ESP32-CYD Firmware Flashing Tool

A simple and easy-to-use firmware flashing tool for the ESP32-CYD device, designed for the SmartGauge Mazda2 Skyactiv project.

📥 Downloads
🖥️ REDLINE Flasher

Download the Windows flashing utility created by Birdlab.

File: REDLINE-Flasher-windows.exe
Author: Birdlab
Platform: Windows
⚙️ SmartGauge Firmware

Download the firmware for SmartGauge Mazda2 Skyactiv.

File: SmartGauge-Mazda2Skyactiv.bin
Device: ESP32-CYD
Purpose: SmartGauge Mazda2 Skyactiv firmware
🔧 Flashing Instructions

Follow these steps to install or update the firmware on your ESP32-CYD.

1. Connect Your Device

Connect the ESP32-CYD to your PC using a USB cable that supports data transfer.

2. Launch REDLINE Flasher

Run the application:

REDLINE-Flasher-windows.exe

3. Configure Flashing Settings

Select the following settings in REDLINE Flasher:

Setting	Value
COM Port	Select the correct port
Panel	invert
Display	80 MHz
Install	factory for first installation
Install	update for firmware updates
4. Select Firmware

Click Browse and select the firmware file:

SmartGauge-Mazda2Skyactiv.bin

5. Flash Firmware

Click Flash to start the flashing process.

Wait until the operation is complete. Do not disconnect the USB cable while flashing.

6. Restart

Once flashing is complete, the ESP32-CYD will restart automatically and load the new firmware.

✅ Recommended Settings

For the first installation, use the following configuration:

Parameter	Recommended Value
Panel	invert
Display	80 MHz
Install	factory
Firmware	SmartGauge-Mazda2Skyactiv.bin
Note: When updating an existing installation, select update instead of factory.
⚠️ Important Notes
Ensure the correct COM Port is selected before flashing.
Use a reliable USB data cable.
Do not disconnect the device during the flashing process.
Make sure the firmware file matches your intended device and project.
👨‍💻 Credits

REDLINE Flasher created by Birdlab.

Developed for flashing the SmartGauge Mazda2 Skyactiv firmware to ESP32-CYD devices.

<p align="center">
<b>REDLINE Flasher</b><br>
<i>SmartGauge Mazda2 Skyactiv · ESP32-CYD</i>
</p>
