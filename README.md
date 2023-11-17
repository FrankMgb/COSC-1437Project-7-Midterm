# WiFi Device Management System

# Purpose

The purpose of the WiFi Device Management System is to simulate the management of different WiFi devices. It serves as an educational tool to demonstrate the concepts of abstract classes and inheritance in Java. The system allows users to interact with simulated devices, providing a hands-on experience with object-oriented programming principles.

## Compilation and Execution

To compile and run the WiFi Device Management System, you'll need a Java Development Kit (JDK) installed on your computer. Open a terminal or command prompt and navigate to the project directory where the .java files are located. Compile the project using the following command:

<img width="284" alt="image" src="https://github.com/FrankMgb/COSC-1437Project-7-Midterm/assets/93266730/0666f4fc-6f70-412c-82e0-4fc489c16650">
This will compile all Java files in the com.abstractdevices package. Once compiled, run the application using the Java interpreter:


<img width="301" alt="image" src="https://github.com/FrankMgb/COSC-1437Project-7-Midterm/assets/93266730/712323f5-9aac-438b-b522-2f281a4e1581">

This command will execute the WifiDeviceDemo class, which contains the main method and will start the user interface of the system.


# Lessons Learned

During the development of this project, several key insights were gained:

The importance of object-oriented principles such as abstraction, encapsulation, inheritance, and polymorphism.
Understanding how to structure a project using packages for better organization.
one thing i really do feel more comfortable about now is Error handling and input validation in Java.
<img width="373" alt="image" src="https://github.com/FrankMgb/COSC-1437Project-7-Midterm/assets/93266730/a487ff65-5914-40fe-ab0d-e0d6ca986e6f">


# Abstract Classes and Methods

Abstract classes and methods play a crucial role in this project. They form the backbone of our system, allowing us to define a generic blueprint for a WiFi device (WifiDevice class) while leaving the implementation details to the specific subclasses (Router and Smartphone). This use of abstraction facilitates code reuse and provides a clear contract for what a WiFi device should be capable of, without constraining how the specifics are implemented.
This is a method being used in the WifiDevice class
<img width="236" alt="image" src="https://github.com/FrankMgb/COSC-1437Project-7-Midterm/assets/93266730/0acd4ad2-b897-4e74-8286-96ba96ac4a1c">


# Functionalities

Connect a WiFi Device
Display Device Information: Outputs the details of the WiFi devices, such as device name and IP address.
Update Router Firmware: Allows the user to update the firmware version of a router.
Install App on Smartphone: installation of applications, such as instagram on a smartphone.
Exit: stops the program.
![image](https://github.com/FrankMgb/COSC-1437Project-7-Midterm/assets/93266730/207a823e-5c97-4113-b25c-bc1b2990e6ca)
