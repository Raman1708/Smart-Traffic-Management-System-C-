# Traffic Management System 
## Overview
This is a project developed as part of an educational exercise to practice Object-Oriented Programming (OOP) concepts in C++. The system simulates a Traffic Management System, handling various vehicle types like cars, motorcycles, and trucks.




## Interface:
<img width="360" height="490" alt="image" src="https://github.com/user-attachments/assets/dc05a1a3-1bb8-4682-aac4-6f291e15e5f9" />
<img width="360" height="490" alt="Screenshot 2025-07-26 163401" src="https://github.com/user-attachments/assets/671e9cab-ed71-45a4-be3d-2f955873ee8b" />



## Features

- **Vehicle Base Class**: A base class `Vehicle` stores general information for vehicles.
- **Derived Classes**:
  - `Car`
  - `Motorcycle`
  - `Truck`
  These classes extend the functionality of the `Vehicle` class.
- **Traffic Control Center**: A `TrafficControlCenter` class manages and controls the flow of vehicles in the system, using random numbers to simulate real-world traffic conditions.
- **File Handling**:
  - Stores traffic data in `trafficdata.txt`.
  - The traffic data is written to the file for further analysis or record-keeping.
- **Auto-Detect and Manual Entry Options**:
  - **Auto-Detect System**: Automatically generates traffic data using random numbers.
  - **Manual Data Entry**: Allows users to manually input vehicle details.
- **Tax Application**:
  - Calculates tax based on the type of vehicle, with different rates for cars, motorcycles, and trucks.
- **Additional Functionalities**:
  - Includes extra classes to enhance user interaction and clarity.
  - The system is designed to be automatic and user-friendly, though still in development.
- **User Authentication:**:
  - A preset login system with the following credentials:
    
    - Username: `raman`
    - Password: `1234`

## Usage Instructions

### How to Run:
1. Create file `trafficdata.txt` in the same folder as the program.
2. Open the file named `Traffic Management system.cpp`.
3. Compile the Program using any C++ compiler like **Dev C++**.
4. Run the Program.

### Input:
- **Auto-Detect**: Generates random traffic data for cars, motorcycles, and trucks.
- **Manual Input**: The user can manually enter details for each vehicle.

### Output:
- Displays vehicle traffic data and tax information.
- Saves all data in `trafficdata.txt` file.




