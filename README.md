# USER APP

- This example code is used for stm32h7 bootloader demonstration 

- configure four 0.5 Hz blinking LED (Timer Output Compare Mode)

- user app starts at address 0x0802_0000

- Aside from adjusting flash address to 0x802_0000, the vector table offset has to be modified to 0x2_0000 in system_stm32h7xx.c as well.

[**stmh743zi bootloader app**](https://github.com/JOSEPH129009/stm32h7_bootload_app) \
[**linux serial app**](https://github.com/JOSEPH129009/serial-port-echo-programming) \
[**video demonstration**](https://www.youtube.com/watch?v=dADT_mSCsA4)

### Microcontroller Configuration

![link](image/Screenshot%20from%202022-11-13%2017-12-42.png)
![link](image/Screenshot%20from%202022-11-13%2017-12-53.png)