# INEX Arduino STM32 core addon for INEX's STM32 products

Last update :

1 Oct 2024 : Temporary workaround, change packed file to alternate host (Issue : Host response Forbidden 403).

28 Sep 2024 : Annoucement all users for next update Arduino Core STM32 Core system to version 2.8.x , which no longer support on Arduino 1.8.x (and also 32bit PC machine)

On next, need migrate to Arduino 2.x and no old Arduino 1.8.x (which cause Arduino AppData folder conflict issues)

If not , select not update and still on 2.4.0 POP-32 library set instead, Regards.

23 Feb 2023
 : (library) POP32.h update, add 10 sec. Booting timeout if hold SW_A on start (for HID Boot recovery)

17 Jan 2023  
 : (Library) POP32.h update, fixed PWM motor glitch on repetitive command  
 : (Upload system) introduce upload method using STMicroelectronics ST-Link V2 SWD  
 
3 Jan 2023  
 : (Update TEST) update internal STM32 core to 2.4.0
 
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
on HID mode, no additional driver needed.

on SWD mode, using ST Microelectronic's STM32 CubeProgrammer driver.

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
