Problem statement

Managing resident and visitor vehicle parking in residential complexes is often done manually, leading to errors in slot allocation, poor visibility of parked vehicles, and difficulty tracking check-in/check-out times. This results in inefficient use of limited parking slots and frustration for both administrators and vehicle owners. The project addresses this by providing a structured, programmatic way to register vehicles, manage their parking status, and view all parking information in one place.
Scope of the project

The project focuses on a single-parking-area scenario where both resident and visitor vehicles are tracked using a Java application with an integrated GUI. It covers basic operations such as adding vehicles, marking check-in/check-out for residents, setting out-time for visitors, counting currently parked vehicles, and displaying all vehicle details. Integration with external systems (e.g., payment gateways, sensors, ANPR cameras) and multi-site management are outside the current scope but can be considered as future enhancements.
Target users

    Residential apartment associations or gated community management teams who need to maintain a digital record of resident and visitor vehicles.

    Security staff or parking attendants who handle day-to-day check-in/check-out and need a simple GUI instead of paper registers.

    Students and developers who want to understand and extend a basic object-oriented parking management solution using Java and Swing.

High-level features

    Registration of resident vehicles with persistent parking status and flat/owner details.

    Registration of visitor vehicles with in-time and out-time fields and automatic slot release when visitors exit.

    Check-in/check-out functionality based on vehicle registration number for residents.

    Counting and displaying the number of currently parked resident and visitor vehicles.

    Consolidated display of all registered vehicles, grouped as resident and visitor, through a GUI panel.

    Error handling using custom exceptions for cases like no available parking slot or invalid vehicle registration number.
