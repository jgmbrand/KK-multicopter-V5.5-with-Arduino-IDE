# KK-multicopter-V5.5-with-Arduino-IDE

Found an OLD (crashed) KK Multicopter board and decided to have some fun with the onboard gyros and potentiometers.  
The board has an ATmega168PA that uses the internal 8MHz osc. 
  

**KK Multicopter Blackboard V5.5**
![](https://github.com/jgmbrand/KK-multicopter-V5.5-with-Arduino-IDE/blob/master/Hardware/KK-Mulicopter1.jpg?raw=true)

Modified the hardware by adding a Serial interface (FTDI) to enable communication with the Arduino IDE. 

**KK Multicopter board without modifications**
![](https://github.com/jgmbrand/KK-multicopter-V5.5-with-Arduino-IDE/blob/master/Hardware/KK1.jpg?raw=true)

**KK Multicopter board with modifications**
![KK Modifications](https://github.com/jgmbrand/KK-multicopter-V5.5-with-Arduino-IDE/blob/master/Hardware/KK_arduino.jpg)  
  
**FTDI Connections**    

Power,Ground and the KK-TX(FTDI-RX) signal can simply be taken from the receiver **RX Roll** connector.  
For the KK-RX(FTDI-TX) signal a thin wire must be soldered to the (free)pin 30 of the ATmega chip.  
The FTDI-DTR(KK-RESET) signal must be connected to C10.   
Therefore C10 must be disconnected from Ground by lifting it up, away from the Ground pad and then soldering a thin wire to the open "pin" of C10. 
  
**Bootloader programming**  
tbd.

**Demo program**  
tbd.
   
 




