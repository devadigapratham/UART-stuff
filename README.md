
# UART Transmitter and Receiver Design using Verilog and Intel Quartus

This project involves designing UART Transmitter and Receiver modules using Verilog and Intel Quartus. The UART Receiver is responsible for receiving input UART data packets according to the specified parameters and outputting the received message (`rx_msg`) upon completion of the entire packet reception. Additionally, the `rx_complete` signal toggles for 1 clock cycle upon packet reception. On the other hand, the UART Transmitter takes 8-bit input data to transmit and generates the `tx` signal as a UART data packet in a serial format.

## UART Receiver

### Description
The UART Receiver module, implemented in Verilog using Intel Quartus, receives input UART data packets based on the specified parameter table. Upon detection of the `rx` input signal, it processes the received data and outputs `rx_msg` after the entire UART data packet is received. Simultaneously, the `rx_complete` signal toggles for 1 clock cycle to indicate the completion of packet reception.

## UART Transmitter

### Description
The UART Transmitter module, implemented in Verilog using Intel Quartus, receives 8-bit input data indicating the character or data to transmit. Based on this 8-bit data input, it generates the `tx` signal as a UART data packet in a serial format for transmission.

## Implementation Details

Both the UART Transmitter and Receiver modules are implemented in Verilog using Intel Quartus. They are designed for integration into larger hardware designs or FPGA projects for serial data communication.
