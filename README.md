# Embedded Rust-based Drone

Welcome to my organization for my Drone project, a space where I am developping my skills in embedded technologies by building an embedded flight controllers using embedded Rust and the STM32 microcontroller. I am using this organization to house and isolate aspects of the flight controller, and then develop a a final repository for the entire flight controller. The projects/aspects of a flight controller I have identified are listed below. 

## Featured Repositories

[**LSM6DSOX-Kalman-Filter**](https://github.com/KG-Drone-Project/LSM6DSOX-Kalman-Filter)
   - *Status: Completed*
   - I've implemented a Kalman Filter in Rust for sensor fusion, combining accelerometer and gyroscope data to achieve accurate attitude estimation.

[**ESC-Controller**](https://github.com/KG-Drone-Project/ESC-Controller)
   - *Status: Completed*
   - Generated PWM signals to drive the brushless motors.

[**FlySky-Receiver**](https://github.com/KG-Drone-Project/FlySky-Receiver)
   - *Status: In Progress*
   - This repository is a work in progress for FlySky Radio receiver integration.
   - Currently, the IBUSBM protocol working which is essentially uart communication.
   - Data processing needs to be completed

**PID Control** 
  - *Status: Pending*
  - I will implement a Proportional-Integral-Derivative (PID) controller.
  - Will enhance the system's stability and responsiveness.

## About RTIC and Rust

My projects leverage the Real-Time Interrupt-driven Concurrency (RTIC) framework to handle concurrent tasks efficiently. Rust, with its focus on memory safety and performance, serves as the primary programming language, ensuring the reliability of my flight controllers. 

Join me on this journey to redefine embedded flight control systems. Happy flying!
