# Porting-PetaLinux-15.4-to-18.3-for-Zynq7000-ZC702-
Ports the Petalinux OS from 15.4 to 18.3 for Zynq 7000

Note : This project is for accessing HDMI screen using ZC702

For booting OS in your ZC702 board 
Copy the BOOT.bin and image.ub in your SD card and load it inside your FPGA and power up

For Building your own OS,

1.build using the given .hdf & .bit file with your petalinux

2.Replace the existing system-user.dtsi with the file provided and rebuild

Then you have petalinux 18.3 working in your ZC702 board

You might have to purchase Xylon LogiCVC framebuffer and get the patch file for kernel from them
