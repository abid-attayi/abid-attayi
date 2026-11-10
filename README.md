# Abid Attayi

**Mechatronics Engineering @ University of Waterloo · Embedded Systems Validation Co-op @ onsemi**

*Writing the code that sits right on top of the hardware.*

I'm focused on embedded systems and firmware: device drivers, RTOS internals, and bringing up boards from the reset vector. Coming from validation and test, I also care about proving it works on real silicon, not just that it compiles.

### Things I've built that run on real hardware

* ⏱️ Pre-emptive RTOS kernel in C for the ARM Cortex-M4, with its own scheduler, context switching and system calls
* 🛩️ CAN data logger for a UAV that decodes and stores 200+ frames per second as black-box flight data ([WARG](https://www.uwarg.com/))
* 🔌 Remote flash-and-debug station that lets a team program STM32 flight controllers without being in the lab
* 🧪 Automated test bench work at onsemi that validated 40+ sensors on a mixed-signal ASIC
* 🔧 [STM32 firmware from scratch](https://github.com/abid-attayi/stm32f401-bare-metal): my own startup code, linker script and Makefile, no IDE or vendor files

### Currently

Building a custom bootloader on top of the bare-metal project.

**Tools:** C/C++ · Python · STM32 · ARM Cortex-M · SPI / I2C / UART / CAN · OpenOCD

[LinkedIn](https://linkedin.com/in/abid-attayi/) · Open to Summer 2027 embedded and firmware co-ops
