# Real-Time-Sensor-Monitoring-Station
Real-Time sensor Monitoring Station using ARM7 LPC2129,ADC,UART and Periodic task scheduling.

# Real-Time Sensor Monitoring Station Using Periodic Task Scheduler

## 1. Project Overview

The Real-Time Sensor Monitoring Station is an embedded systems project developed using the ARM7 LPC2129 microcontroller.

The system monitors multiple sensor parameters periodically using a timer-based task scheduling approach. It collects sensor data, processes the readings and sends the monitoring information through UART communication.

## 2. Objectives

- To monitor multiple sensor parameters.
- To implement periodic task scheduling using a hardware timer.
- To interface sensors with the ARM7 LPC2129 microcontroller.
- To display sensor information through UART communication.
- To understand real-time embedded system concepts.

## 3. Hardware Requirements

- ARM7 LPC2129 development board
- Temperature sensor
- Light sensor (LDR)
- Potentiometer
- Vibration sensor
- Flame sensor
- LEDs and buzzer
- Connecting wires

## 4. Software Requirements

- Embedded C
- Keil µVision
- UART terminal
- ARM7 LPC2129 development environment

## 5. Technologies and Concepts Used

- Embedded C programming
- ARM7 microcontroller
- ADC interfacing
- GPIO interfacing
- UART communication
- Timer interrupt
- Periodic task scheduling

## 6. Working Principle

The LPC2129 microcontroller periodically reads sensor values using ADC and GPIO interfaces.

The timer provides periodic scheduling. The collected sensor readings are processed and the monitoring information is transmitted to a computer through UART communication.

## 7. Project Structure

- `sensor_station.c` – Main application program
- `adc_driver.c` – ADC driver
- `uart0_driver.c` – UART communication driver
- `timer_int.c` – Timer interrupt implementation
- `header.h` – Header file

## 8. Applications

- Environmental monitoring
- Basic industrial safety monitoring
- Embedded system monitoring applications

## 9. Future Improvements

- Add data logging.
- Improve real-time sensor response.
- Add wireless monitoring.
- Develop a graphical monitoring interface.

## 10. Conclusion

This project provides practical experience in ARM7 microcontroller programming, sensor interfacing, peripheral communication and timer-based periodic task scheduling.
