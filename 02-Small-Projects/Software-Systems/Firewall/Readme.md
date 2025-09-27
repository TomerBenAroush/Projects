Firewall in C++

About the project - implemention of Firewall mechanism: 

This project implements a firewall that filtered information according to a predefined set of rules.

Given IP and Port from Packet, the firewall verifies if they are in the appropriate range.

The project used C++ to construct a simple program, 
and Bash for parsing the rules and inputting them into the program.

Three main emphasis points of this exercise were:
1. Accuracy - ensuring that the information was filtered as required.
2. Memory efficiency - demonstrating that with C++.
3. Efficiency - measuring the runtime of my program.

About the files in the Project: 

ip.h and ip.cpp: Defines the ip class for handling IP addresses. It includes functionality for setting IP values, matching packets, and setting IP rules.

port.h port.cpp :  Defines the port class for handling port numbers. It includes functionality for setting port values, matching packets, and setting port rules.

string.h and string.cpp: Defines the String class for string manipulation. It includes functionality for string comparison, splitting, conversion to integers, and trimming.

generic-field.h: Defines the GenericField class, which is a base class for the ip and port classes that inherit from it. This includes functionality common to both classes.
