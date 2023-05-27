# b460f-hackintosh-efi
A working EFI folder for the hackintosh community, compatible with the Asus B460-F motherboard

You will need to setup the USB remapping yourself (UTBMap.kext).

Working:
Wifi for Intel Cards (Intel AX200),
Ethernet for Intel NIC (the one that is in the B460-F),
Some USB ports

Broken: Intel Bluetooth (Intel AX200)

For use with other wifi/bluetooth cards remove IntelBluetoothFirmware.kext, BlueToolFixup.kext and IntelBTPatcher.kext
(and add whatever you need accordingly)

INTENDED TO BE USED WITH THE INTEGRATED GRAPHICS OF YOUR INTEL 10TH GEN CPU
