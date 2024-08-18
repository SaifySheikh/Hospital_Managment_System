

```markdown
# Hospital Management System

This project is a Hospital Management System implemented in C++ using Object-Oriented Programming (OOP) principles. It manages various aspects of hospital operations, including appointments, patients, doctors, nurses, drivers, and ambulances.

## Features

- **Appointments Management**
  - Book an appointment
  - Get appointment details
  - Show all appointments

- **Patient Management**
  - Register a new patient
  - Get patient details
  - Hospitalize a registered patient
  - Report a patient's death
  - Discharge a patient or their body
  - Fetch patient details from history
  - Get details of all registered patients

- **Doctor Management**
  - Register a new doctor
  - Get doctor details
  - Remove a doctor
  - Fetch doctor details from history
  - Get details of all registered doctors

- **Nurse Management**
  - Register a new nurse
  - Get nurse details
  - Remove a nurse
  - Fetch nurse details from history
  - Get details of all registered nurses

- **Driver Management**
  - Register a new driver
  - Get driver details
  - Remove a driver
  - Fetch driver details from history
  - Get details of all registered drivers

- **Ambulance Management**
  - Add an ambulance
  - Send an ambulance
  - Get ambulance details
  - Report ambulance arrival
  - Remove an ambulance
  - Fetch ambulance details from history
  - Get details of all registered ambulances

## Project Structure

- **main.cpp**: Contains the main function and the user interface for managing appointments, patients, doctors, nurses, drivers, and ambulances.
- **include/**: Directory containing all the header files for various classes and global variables.
  - `global.hh`: Contains global variables and constants used throughout the project.
  - `hospital.hh`: Contains the `hospital` class that manages global operations for the hospital.
  - `address.hh`: Defines the `address` class for storing address information.
  - `person.hh`: Abstract base class for all personnel in the hospital.
  - `appointment.hh`: Defines the `appointment` class for handling appointment-related operations.
  - `patient.hh`: Defines the `patient` class for handling patient-related operations.
  - `doctor.hh`: Defines the `doctor` class for handling doctor-related operations.
  - `nurse.hh`: Defines the `nurse` class for handling nurse-related operations.
  - `driver.hh`: Defines the `driver` class for handling driver-related operations.
  - `ambulance.hh`: Defines the `ambulance` class for handling ambulance-related operations.

## Usage

1. **Compilation**:
   To compile the project, use the following command:
   ```bash
   g++ -o hospital_management main.cpp -I./include
   ```

2. **Running the Program**:
   After compiling, run the executable:
   ```bash
   ./hospital_management
   ```

3. **Navigating the Menu**:
   - Upon running the program, you will be presented with a menu to choose a category (Appointments, Patients, Doctors, Nurses, Drivers, Ambulances).
   - Navigate through the options by entering the corresponding numbers.
   - Follow the prompts to manage the hospital operations.

## Data Persistence

- Data is stored in CSV files for each category (appointments, doctors, patients, nurses, drivers, ambulances).
- Upon each run, the program loads data from these files and saves any changes before exiting.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, feel free to create an issue or submit a pull request.
