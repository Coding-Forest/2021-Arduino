
## **74HC595** Integrated Circuit

<img src="https://github.com/Coding-Forest/2021-Arduino/blob/main/images/74HC595N-IC.png" width=500 />


**74HC595**
- This shift register works on Serial IN Parallel OUT protocol. 
- It receives data serially from the microcontroller 
- and sends out the data through parallel pins. 

**VCC** (Voltage Common Collector)

**DATA IN**: data is sent to IC by pulses of high / low volatages with synchronisation of clock signal
  - 5V = 1
  - 0V = 0
 
**RCLK**: refreshes the output of IC even after data is sent to IC. It will not show output until it is turned high.

**CLOCK**: a consistent high / low signal with fixed frequency. This works as data shifter for registers. 

**Register**: a processor register is a quickly accessible location available to a computer's processor. Registers usually consist of a small amount of fast storage, although some registers have specific hardware functions. May be read-only or write-only.

**Ground pins**
