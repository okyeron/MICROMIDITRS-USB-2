# MICROMIDITRS-USB-2 

A USBMIDI to TRS MIDI adapter based on the rp2040 microcontroller

### Features

* Auto sensing TRS MIDI Type-A/Type-B Input with [LPZW](http://leipzigwest.org/) Auto Crossover circuit
* TRS MIDI Type-A Output
* Activity LEDs for MIDI input/output
* USB-C


### Firmware

Firmware is available as a pre-compiled UF2 file. See [Releases page](https://github.com/okyeron/MICROMIDITRS-USB-2/releases) for download

To load the firmware, connect the device to your computer and then hold the BOOT and RESET buttons on the MMTRS-USB and then release the RESET button before the BOOT button - this will drop it into bootloader mode. This should now show you a RPI_RP2 drive on your computer desktop. Drag the UF2 file to RPI_RP2 and it should dismount/reboot and come back as the `MMTRS-USB2`.



