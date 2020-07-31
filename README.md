# ESP-01-Tamer
Breadboard-friendly breakout, level shift and programming adapter for ESP-01 ESP8266 module.

This little board makes it super easy to use the ESP-8266 ESP-01 board in the Arduino environment.  

The following features are provided:  
- CH340G based USB serial interface  
- Auto control of RST/IO0 for downloading (uses DTR and RTS)  
- Onboard 3.3v regulator  
- Bidirectional 5v/3.3v logic level conversion on Rx, Tx, IO0, IO2  
- Breadboard-friendly breakout of all essential pins  

There are two versions of this board:  
ESP-01_Tamer   - all above features, with a USB A male connector to host  
ESP-01_Tamer-u - all the same features, but with a micro USB female conneector to host  

Common parts list:  
R1-R9 -   10K 0805 size  
R10,R11 - 470 ohm 0805 size  
R12,R13 - 10K 0805 size  
Y1 - 12mhz SMD-3 ceramic resonator  
IC1 - LD117AS33TR SOT223 3.3v 3-terminal regulator  
IC2 - CH340G USB to serial interface  
D1 - B5819W-TP SOD123 Schottky diode  
C1,C4 - 100nf 0805 size  
C2,C3 - 10uf 0805 size  
Q1-Q4 - 2N7002 SOT23  
Q5,Q6 - S8050 SOT23  
JP1 - 2x4 0.1" thru-hole female header  
JP2,JP3 - 1x4 0.1" thru-hole male header  

USB-A version only:  
JP4 - USB A male thru-hole PCB connector  

Micro-USB version only:  
JP4 - 1x1 0.1" thru-hole male header (in case you need the micro USB ID pin)  
J1 - Hirose  ZX62D-B-5PA8 micro USB female surface mount connector  

PC boards are available on OSHpark:  
USB-A:  <https://oshpark.com/shared_projects/sAVimhVZ>  
microUSB: <https://oshpark.com/shared_projects/1ui7zgvW>  

