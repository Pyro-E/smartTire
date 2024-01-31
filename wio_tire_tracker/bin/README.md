DeviceApp : Application binary
ProvisionBin_62095db8-df60-4800-89cc-ed67e33568ab : provision binary
wio_tracker_1110_bootloader-0.7.0_nosd : UF2 bootloader , it should be flashed first using nrf connect app.

Steps to flash
1. flash the uf2 bootloader (wio_tracker_1110_bootloader-0.7.0_nosd.hex) using nrf connect programmer
2. After flashing this there will appear a drive (WM1110_BOOT) in file explorer
3. Drag and drop provision binary ProvisionBin_62095db8-df60-4800-89cc-ed67e33568ab.uf2 to this drive
4. Drag and drop application binary DeviceApp.uf2 to this drive.
