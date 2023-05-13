# picostation_pcb

![PCB](./images/top.png "PCB") ![builtin](./images/builtin.jpg "builtin")

This is my adaption of the PicoStation PCB for [paulocode](https://github.com/paulocode)s [PicoStation](https://github.com/paulocode/picostation).  
This layout was made to be completely purchaseable by JLCPCB therefore all partsnumbers etc. are included in the Project.

---

## NOTICE ##
for this board to properly work the crystal-wait time needs to be extended.  

For this you need to add the follwing lines in CmakeLists.txt under "add_executable(picostation)" :

>target_compile_definitions(  
>picostation PUBLIC  
>PICO_XOSC_STARTUP_DELAY_MULTIPLIER=64  
>) 



---

 - The FFC cable is the same one that comes with an Xstation
