# RUMBA_BTT
Several issues with bigtreetech rumba32 board and Marlin2.0 

I have the rumba32 bigtreetech board  (BIGTREETECH Rumba32 V1.0 180MHZ 32-Bit) with TMC2209 stepper drivers (UART MODE) and I
have a lot of issues getting it to work properly. 
I have spent already many hours in vain for getting the board to work. I hope to gather real working solutions.


MY CONFIGURATION

I use Marlin 2.0 with the bugfixes and configuration files. The (X, Y, and X motors can move)
I did not want sensorles homing and use my "normal" endstop switches for X and Y (which worked fine on my previous Marlin 1.19)
For this reason I have cut from the TMC2209 stepper drivers the DIAG signal pin. 


OPEN REMAINING ISSUES:

ISSUE#1 My BLtouch does not work

The +,  the - , the black the white wire is easy leaving one signal wire left which should be somewhere on the EXP3 connector.
I found on github some info stating that I should NOT use the EXP3 port but 1 of the encoders. But it is totally unclear which wires
/signals are needed to get it working. 
Is there anybody out there who has above configuration and has the bl touch working in combination with TMC2209 stepper drivers?
A few pics about the correct pins would really help.


#ISSUE #2 The RRD Graphic Smart Controller shows a startupscreen but after entering the menus the screen freezes and the display or board seems to reset.
(It shows the Marlin 2.0 startscreen again.)


ISSUE #3 The board was deliverd with 6 jumper cables. I followed the Manual from BIGTREE TECH and AS3D but I am not sure if I need these cables?
(The motors work)
If needed for UART mode can someone tell me how to connect these jumper wires? (Preferably a clear picture / sketch for dummies) 

Any help would be very appreciated!

Regards JWD
