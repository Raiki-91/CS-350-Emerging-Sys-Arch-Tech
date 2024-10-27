# CS-350-Emerging-Sys-Arch-Tech
## Project Summary
The thermostat project involved developing an embedded system that monitors and controls room temperature using a microcontroller. The primary objective was to create a functioning thermostat capable of reading room temperature, adjusting a set-point using button inputs, and indicating heater status through an LED. Additionally, the system reports temperature readings, heater status, and system uptime via UART to simulate server communication. The project tackled the challenge of managing multiple peripherals (I2C, UART, GPIO, Timer) and integrating them into a cohesive, real-time system that responds accurately and efficiently.

## Achievements
One area where I performed particularly well was in the development of the task scheduler, ensuring that all peripheral operations (temperature readings, button inputs, and UART communication) executed at their specified intervals. I successfully integrated the peripherals and maintained a consistent state machine flow that effectively manages the thermostat's functionality in real-time.

## Areas for Improvement
While the project was successful, I could improve my ability to troubleshoot hardware-related issues more efficiently. Initially, I encountered several problems with the temperature sensor's I2C communication, which required further debugging and adjustments in I2C speed. Gaining deeper insight into hardware-level diagnostics would streamline future debugging processes.

## Tools and Resources Added to My Support Network
Throughout the project, I expanded my knowledge of microcontroller development tools, specifically those related to Texas Instruments' Code Composer Studio, I2C communication protocols, and timer peripherals. Additionally, I familiarized myself with TI's documentation, online forums, and other resources to effectively troubleshoot and implement functionalities.

## Transferable Skills
The skills developed during this project, particularly in task scheduling, state machine implementation, and integrating peripherals like I2C, UART, and GPIO, are highly transferable to other embedded system projects and coursework. These core concepts are fundamental in building responsive, real-time applications and will be valuable in future endeavors involving microcontrollers and embedded programming.

## Code Maintainability, Readability, and Adaptability
I ensured that the project code remains maintainable, readable, and adaptable by following best coding practices such as modularity, comprehensive commenting, and consistent formatting. Each peripheral's initialization and use are encapsulated in well-defined functions, making it easy to identify and update specific functionalities. Furthermore, I employed a state-machine architecture, which makes it straightforward to modify system states or add new functionality as the project evolves. By structuring the code in this manner, future developers (or myself) can adapt the thermostat system to new requirements or different hardware configurations with minimal effort.
