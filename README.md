# ETHERNET STM32H755ZI

This is an example code where for the NUCLEO-H755ZI-Q board.

This example just use the the M7 core for the ethernet. 
The Ip is statically assigned.
It also contain udp server running as a thread.
FreeRTOS is used as well for this purpose.

# How to run the example

In the `lwip.c` file inside the `LWIP/APP` folder change the IP address to the gateway IP address of your own.
Ping the Ip address you assigned statically to test the ethernet coonection.
