# Porting FreeRTOS on CC2538

This project ports FreeRTOS to CC2538. Following lines decribes the work required for a successful basic port. 

1. Set-up a Cross-Compilation development workspsace in Eclipse and CCS Studio for CC2538 SOC Chip.
2. Add and Compile FreeRTOS-Core modules to the current bare-metal stack on the CC2538 SOC chip. 
3. Validate the port by a FreeRTOS test application which uses UART and GPIO pheripherals.
