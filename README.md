# SMART-INDUSTRIAL-SAFETY-MONITORING-using-LPC2129

Overview

This project is an ARM7-based industrial safety monitoring system developed using the LPC2129 microcontroller and Embedded C as a mini project.

The system monitors temperature, worker movement, and flame detection. Based on the sensor inputs, the LPC2129 processes the data and determines the current safety condition.

Microcontroller
* Microcontroller: LPC2129
* Architecture: ARM7
* Programming Language: Embedded C

Sensors Used
* LM35 – Temperature monitoring
* PIR Sensor – Worker/motion detection
* Flame Sensor – Fire/flame detection

Peripherals Used
* GPIO
* ADC
* UART
* 16×2 LCD
* LEDs

Working

The LPC2129 reads the sensor inputs and processes them to determine the current safety condition.

Temperature

The LM35 provides an analog output which is read using the LPC2129 ADC. The ADC value is converted into the corresponding temperature.

PIR Sensor

The PIR sensor provides a digital signal to detect worker movement/presence.

Flame Sensor

The flame sensor detects the presence of a flame and provides a signal to the LPC2129.
The flame sensor works by sensing infrared light emitted by a flame.
