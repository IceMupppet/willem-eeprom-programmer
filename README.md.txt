# Willem EEPROM Programmer files

## Install

 * Set LPT (Parallel Port) to ECP mode in the BIOS.
 * In Device manager, allow the port to accept interrupts and enable legacy mode operation as well.
 * install TVicPortInstaller41
 * install EPROM50 via setup_PCB50_98D12C3
 * change io.ini to have the address of your Parallel port if necessary
 * copy over to EPROM50 directory  (C:/program files (x86)/EPROM50/)
 * restart computer 

## Configure
Change ````io.ini```` to have the parallel port address found in device manager.

 * Default is 0x378 

### Thanks to Doug Brown for his work on this project to make it possible to use the Willem EEPROM Programer on x64 Windows 7.

[Doug Brown](http://www.downtowndougbrown.com/2010/10/sivava-willem-eprom-programmer-on-windows-7-64-bit/)