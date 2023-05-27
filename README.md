# b460f-hackintosh-efi
A working EFI folder for the hackintosh community, compatible with the Asus B460-F motherboard

You will need to setup the USB remapping yourself (UTBMap.kext)

YOU WILL NEED TO PROVIDE YOUR OWN RESOURCES FOLDER, AS GITHUB DOESN'T ALLOW UPLOADS OF TOO MANY FILES (and splitting uploads is time consuming).
This is an opprotunity to learn to customized your OpenCore EFI. (https://dortania.github.io/OpenCore-Post-Install/cosmetic/gui.html).


Working:
Wifi for Intel Cards (Intel AX200),
Ethernet for Intel NIC (the one that is in the B460-F),
Some USB ports

Broken: Intel Bluetooth (Intel AX200)

For use with other wifi/bluetooth cards remove IntelBluetoothFirmware.kext, BlueToolFixup.kext and IntelBTPatcher.kext
(and add whatever you need accordingly)

INTENDED TO BE USED WITH THE INTEGRATED GRAPHICS OF YOUR INTEL 10TH GEN CPU
