# Parking_System
# Parking Management System

## Overview of the project
This project is a Java-based parking management system that allows managing both resident and visitor vehicles, including slot allocation, check-in/check-out, and reporting of parked vehicles. It includes a Swing-based graphical user interface and a console demo to interact with the core parking logic.

## Features
- Add resident vehicles with persistent parking status tracking.  
- Add visitor vehicles with in-time and out-time handling and automatic slot release on exit.  
- Check-in / check-out operations for resident vehicles by registration number.  
- Set out-time for visitor vehicles and handle invalid registration numbers via custom exceptions.  
- Display all vehicles with separate sections for resident and visitor details.
- Count currently parked resident and visitor vehicles.
- Swing GUI with multiple screens (home, add vehicle, check-in/out, set out-time, display details).

## Technologies/tools used
- Java (Core Java, Collections, Streams).
- Java Swing and AWT for GUI (JFrame, JPanel, JButton, JTextField, JTextArea, JScrollPane, CardLayout, JOptionPane).
- Custom exception classes for domain-specific errors (ParkingSlotNotAvailableException, VehicleNotFoundException).  
- Object-oriented design with inheritance (`Vehicle`, `ResidentVehicle`, `VisitorVehicle`).

## Steps to install & run the project
1. Ensure Java JDK (version 8 or above) is installed and added to your system PATH.  
2. Place all `.java` files in a consistent package structure matching the `package` declarations (e.g., `ParkingSystem/Service`, `ParkingSystem/Exceptions`, `ParkingSystem/Test`). 
3. Compile the source files from the project root, for example:
   - `javac ParkingSystem/Exceptions/*.java ParkingSystem/Service/*.java ParkingSystem/Test/*.java`  
4. To run the GUI version, execute:
   - `java ParkingSystem.Test.ParkingManagementGUI`.
5. To run the console demo, execute:
   - `java ParkingSystem.Test.ParkingManagementDemo`.

## Instructions for testing
- Use `ParkingManagementDemo` to quickly test the core logic of adding vehicles, updating out-time, counting resident vehicles, and displaying all vehicles from the console output.
- In the GUI:
  - From the Home screen, choose “Resident” or “Visitor” to switch mode and then use “Add” to register a vehicle. 
  - Use “Set” under “CheckIn/CheckOut” to change resident parking status and verify the count feature for resident/visitor vehicles.
  - Add visitor vehicles, then set their out-time and confirm that the visitor count and available slots update accordingly. 
  - Use the “Display” button on the Home screen to ensure all vehicles are listed correctly in the details panel.

[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/61116094/56270cf1-186e-462b-9028-d2efc3a79e31/ParkingManagementGUI.java)
[2](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/61116094/e6be1168-042d-4687-bcc2-45b347c67958/ParkingManagementDemo.java)
[3](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/61116094/4be8b2d8-9418-4118-87f3-493e289496b0/ParkingManagement.java)
