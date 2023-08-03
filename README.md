# Stm32-DMA
This project demonstrates how to read data from the first two channels of ADC1 and transmit it via UART using DMA (Direct Memory Access). The microcontroller used in this project is STM32F407VGT6, and the code is written in C language using STM32CubeMX and HAL (Hardware Abstraction Layer).

## Project Description
The purpose of this project is to read analog data from two ADC channels and transmit it to an external device, such as a computer, via UART. The ADC is configured in continuous mode to continuously sample both channels. DMA is utilized to transfer the ADC data from the ADC buffer to memory without CPU intervention. This enables efficient and reliable data transmission without burdening the CPU.

