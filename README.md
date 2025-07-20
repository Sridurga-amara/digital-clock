# Digital Clock using Verilog

This project implements a **Digital Clock** using Verilog HDL. It includes modules for time counting (hours, minutes, seconds), binary to BCD conversion, seven-segment display driving, pushbutton debouncing, and clock division. The time is displayed in HH:MM format using a 4-digit 7-segment display, with additional LEDs used to show seconds.

## Project Features

- Real-time hour and minute tracking with second display on LEDs  
- Manual hour and minute increment using pushbuttons  
- Reset functionality to clear the clock  
- Debouncing logic to handle noisy mechanical switches  
- Binary to BCD conversion for display formatting  
- 7-segment display driver for visual time output  
- Clock division to generate human-readable update speeds  

## Usefulness

This digital clock is useful as a foundational FPGA project to:

- Understand real-time digital design and counters  
- Learn clock division, button debouncing, and data display using seven-segment displays  
- Serve as a building block for larger embedded applications such as alarms, timers, or schedulers  
- Practice modular Verilog HDL design principles  

## Advantages

- Simple and modular design – easy to understand and extend  
- Can be used to teach basic digital design concepts  
- Accurate timekeeping when run on a stable clock (e.g., 100 MHz on Basys 3)  
- Hardware-based – works without a microcontroller or software  
- Real-time control through switches and pushbuttons  

## Applications

- Digital wall clocks or desk clocks built with FPGAs  
- Learning and demonstration projects in labs or classrooms  
- Part of a real-time embedded system for scheduling or alarms  
- Timer module in small embedded products or appliances  
- FPGA-based IoT prototypes needing time display  

## Future Improvements

- Add support for seconds display on the 7-segment display  
- Include AM/PM indicator or 12-hour format mode  
- Integrate real-time clock (RTC) module for improved accuracy and battery backup  
- Add alarm functionality with buzzer support  
- Display date and day using additional displays or external LCD  
- Add serial interface (UART/I2C) for PC or IoT integration  
- Store time settings in EEPROM or registers for power-off recovery  
