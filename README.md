# Adaptive-Cruise-Control-system
- This is 2024WN EECS461 Final Project at the University of Michigan. This project is to develop an adaptive cruise control system allowing different lab groups to interact over the network and receive both visual feedback from a computer monitor as well as haptic feedback.
- This project is done by Qinwen Qian and Genevieve Dumont.
  
- The software is written in C to develop the embedded controller for a haptic interface. We implemented the controller over a CAN netwot to study performance degradation due to networking delay. We then recreated our work uysing the rapid prototying tools to generate C code directly from a Simulink model of the haptic cirtual worls.

- 'Final_project.slx' contains a Simulink model that models a simple vehicle and implements an ACC system named 'Final_project.slx'. The 'controllers.m' contains parameters of the controller used.
