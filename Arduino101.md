

**8Shift Registers (74HC595)**

8 bit serial-in, serial or parallel-out shift register without output latches; 3-state

<img src="https://raw.githubusercontent.com/Coding-Forest/2021-Arduino/main/images/74HC595N-IC.png" width=400 />

| Symbol | Pin | Description |
| - | - | - |
| Q1 | 1 | Parallel data output 1 |
| Q2 | 2 | Parallel data output 2 |
| Q3 | 3 | Parallel data output 3 |
| Q4 | 4 | Parallel data output 4 |
| Q5 | 5 | Parallel data output 5 |
| Q6 | 6 | Parallel data output 6 |
| Q7 | 7 | Parallel data output 7 |
| GND | 8 | Ground (0 V) |
| Q7S | 9 | Serial data output |
| MR | 10 | Master Reset (active LOW) |
| SHCP | 11 | Shift Register Clock = Input Clock.<br> Shifts data into memory. |
| STCP | 12 | Storage register clock input = Output Clock<br> |
| OE | 13 | Output enable input (active LOW) |
| DS | 14 | Serial data input = Data Line<br>the value that is put into memory; either 1 or 0. |
| Q0 | 15 | Parallel data ouptu 0 |
| VCC | 16 | Supply voltage |

    A GPIO (general-purpose input/output) port handles both incoming and outgoing digital signals. 
    As an input port, it can be used to communicate to the CPU the ON/OFF signals received from switches, 
    or the digital readings received from sensors. 
    As an output port, it can be used to drive outside operations based on CPU instructions and calculation results—for example, 
    to drive an LED display based on calculation results, or to output drive signals to a motor.

    The GPIO is referred to as "general purpose" because each pin can be freely set to function as either an input or an output. 
    In early MCUs, each port was either exclusively input or exclusively output. 
    A GPIO is flexible, however. If it has 8 pins, you can set them as best suits your needs: 
    4 input and 4 output, or 7 input and 1 output, or any other combination (Renesas, n.a.).
    
**Application of Shift Registers**
 
1) Allows to control an infinite number of outputs using a limited number of input pins (in your Arduino).
  
<br>  
  
 **References**
electronica (2013) The Shift Register: Explained [74HC595] https://www.youtube.com/watch?v=ameNT2MKDyE&ab_channel=electronica
Renesas (N.A.)Essentials of Microcontroller Use Learning about Peripherals: GPIO https://www.renesas.com/us/en/support/engineer-school/mcu-programming-peripherals-01-gpio
