# MATLAB-Turbidity-Sensor
A student project for ENGR114 at Portland Community College. Uses MATLAB to read a turbidity sensor connected to an Arudino over serial.
# Problem Statement
Our group was tasked with creating MATLAB code to call data from an Arduino hooked up to a
turbidity sensor for the hydroponic fish tank-garden in the engineering department. 
Using Arduino and MATLAB the water turbidity will be recorded over a set amount of time with the turbidity displayed at regular intervals.
A plot of the turbidity as a function of time will also be generated for a visual representation of the turbidity.  The Arduino will produce an analog reading for turbidity that is converted to a voltage reading (where more voltage is less turbid water), then which MATLAB outputs the NTU reading for correct tubidity units. This will be used in order to monitor the turbidity of the water in the garden and subsequently the conditions of said garden.
