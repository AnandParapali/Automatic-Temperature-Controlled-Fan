# Automatic-Temperature-Controlled-Fan
I have created a system that would automatically control the rotational speed of the fan based on the temperature of the room. Making sure that people are comfortable.
To make this project I have used 8051 as the MCU. Along with this I have also used a temperature sensor, ADC (Analog to digital converter),Lcd display,motor drivers and a dc motor. The value that we get from the temperature sensor would be analog in nature which nedded to be converted to digital signal and given to the microcontroller. The ADC that i have used is PCF8591. The microcontroller is responsible for displaying data to the LCD display as well as give PWM signal to motor driver.
In the future I would like to add sensors to detect human presence and could be used to turn OFF/ON the fan to reduce the electricity consumption.
To run this project, you would need to have Proteus software and Keil IDE. You would need to generate a hex file of the code in Keil IDE and load it onto the microcontroller and run the simulation in Proteus.  
This project has MIT licensing.
