# Reflow Oven Controller


<p align="center">
  <img src="https://github.com/user-attachments/assets/85ba377f-c54f-4f27-bf6f-f3c5654842bc" width="40%">
  <img src="https://github.com/user-attachments/assets/ac8f2d3f-2507-4534-ab78-aa1741534ffd" width="40%">
</p>

**University of British Columbia — Electrical and Computer Engineering**  
**Course:** ELEC291/ELEC292  
**Instructor:** Dr. Jesús Calviño-Fraga  

---

## Video Discription of Entire Project:   
   
[![Robot Project Video](https://img.youtube.com/vi/zQPqsqj1WKY/0.jpg)](https://www.youtube.com/watch?v=zQPqsqj1WKY)

## Full Documentation Found Here:

[https://docs.google.com/document/d/1leqfYqjzB9zKQ_UTSe2Mh5pUl4m0ZX2J0jO5OBIaCuE/edit?usp=sharing](https://docs.google.com/document/d/1PFDLNDIMLwOCruiKcaoNeSyW8B0Yf_5CcdiZVpvq4EE/edit?usp=sharing)

---

## Hardware Overview
* Microcontroller: DE10-Lite/DE1-SoC 8052 soft processor
* Amplifier: OP07PC
* Capacitors: 2 10uF
* K-type Thermocouple
* Keypad
* Resistor 330 Ohms
* Speaker CEM-1302
* Diode 1N4148
* N-channel MOSFET FQU13N06LS
* DC-to-DC Voltage Converter TCP7660
* Two buttons


## Specifications
* Selectable reflow profile parameters such as soak temperature, soak time, reflow
temperature, and reflow time using pushbuttons or switches and displayed on the LCD
* Display of temperature(s), running time, and reflow process current state on an
LCD
* Selectable large display of oven temperature with 7-
segment displays available on the DE10-Lite boards

* Start/Immediate Stop pushbutton.
  
* Temperature strip chart plot in degrees Celsius using the serial port attached to the processor and a
personal computer

* Sound feedback using speaker. Five beeps when the reflow process is
completed. Ten beeps when there is an error.

## Extra functionality 

# Microwave mode
- has a timer
- has different modes for different foods
- auto ends after timer
- shows timer on LCD
- times and temperatures are perfectly aliged to mimic a microwave
# Keyboard sound mode
- custom music note characters
- allows you to make song
# Two songs you can pick
- 2 fully done songs that will play at the end when its done
- can chose between them  
# Python cool graph
- shows prediction graph by taking in the parameters
- dynamically resizes based on current temp
- changes colour the hotter it is
  
# Discord messaging
- When the cook cycle elapses, members of the community will be notified on discord, so you can monitor your it from wherever you are

## LCD
- State 0: Paramters on the 7 segments, temperature of oven and time on the LCD
- State 1-5: oven temperature on the 7segs, and 2 screens on LCD: one parameters, one oven temperature/total time on first row, second row is progress bar and state running time and state number
