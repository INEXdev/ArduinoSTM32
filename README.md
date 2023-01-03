# INEX Arduino STM32 core addon for INEX's STM32 products

Last update :

3 Jan 2023  
 : <Update TEST> update internal STM32 core to 2.4.0
 
5 Dec 2022  
 : Force PLL system clock initialize 72MHz and USB active.

1 Dec 2022  
 : Update Libraries for INEX's POP-32 board (In development !!!)
 - If you had ever install previous date version, please remove and re-install for new integrity update again.

20 Nov 2022  
 : Update Libraries for INEX's POP-32 board (In development !!!)

22 Oct 2022  
 : first preview for INEX's POP-32 board (In development !!!)

INEX Arduino STM32 core addon  
work on Arduino IDE 1.8.x https://www.arduino.cc/en/software  
for 64bit Windows user can try new Arduino IDE 2.0.2
(In development, testing, If any error please inform me at dev[at]inex.co.th)  

# Board support
POP-32  

# USB Driver
use HID driver, no additional driver needed

# Instruction
(Remark: Fast internet connection and large files transfer required for this procedure)  
Open Arduino, menu File -> Preferences  
look at the bottom > Addition Boards Manager URL then copy below address on field  

https://github.com/INEXdev/ArduinoSTM32/raw/main/package_inex_stm32_index.json

and IMPORTANT! "REMOVE Checkbox "Verify code after upload"
and also disable "Check for updates on startup" keep working on this version.
![alt text](https://github.com/INEXdev/ArduinoAVR/raw/main/EditPreference.png)

click OK, then goto menu Tools -> Board -> Boards Manager  
wait for Arduino check addition URL, then scroll down and looking for "INEX STM32" then click "Install"  
sitting back and wait for get files from internet and Installing...  

If all Okay, you will get all needed file for working with INEX STM32 core products.. Have Fun..  
