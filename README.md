# Hotel Reservation System

## Introduction

The Hotel Reservation System is a command-line application built in C++ to manage room reservations for a hotel. It provides functionalities for both administrators and clients to schedule and view reservations, manage room availability, and update user account settings.

### Features

- **Client Features:**
  - Room reservation scheduling
  - Displaying existing reservations
  - Account settings management

- **Admin Features:**
  - Managing reservation schedules
  - Marking dates as available or unavailable

## Getting Started

### Prerequisites

- **Operating System:** Windows, Linux, macOS
- **Compiler:** GNU GCC Compiler (or any C++11 compatible compiler)

### Installation and Compilation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repository.git
   cd HotelReservationSystem
   ```

2. Compile the source code:

   ```bash
   g++ -o HotelReservationSystem *.cpp -std=c++11
   ```

### Usage

1. Run the compiled executable:

   ```bash
   ./HotelReservationSystem
   ```

2. Follow the on-screen prompts to navigate through the menus:
   - Register or login as a client
   - Schedule room reservations
   - Manage account settings
   - View or manage reservations (admin access)

### Directory Structure

- **Account.hpp:** Header file for Account class handling user registration and login.
- **HRS.hpp:** Header file containing the main logic for the Hotel Reservation System.
- **Account_setting.hpp:** Header file for managing user account settings.
- **Sorted_roomprice.hpp:** Header file for handling sorted room prices.
- **ReservationSystem.hpp:** Header file for the reservation system.

### Dependencies

- conio.h: For console input/output handling.
- fstream: For file handling operations.
- cstdlib: For exit function.
- algorithm: For standard algorithms.
- sstream: For string streaming operations.

## Acknowledgments

- References:
  - C++ Complete Reference
  - Let Us C, 4th Edition by Yashwant Kanetkar

- Web References:
  - [BYJU's Exam Prep](https://byjusexamprep.com/online-test-series)
  - [Pariksha](https://www.pariksha.co)

---

This README provides a brief overview of the Hotel Reservation System, how to compile and run it, the directory structure, dependencies, contributors, license, and acknowledgments. Adjust the placeholders and references as needed to match your specific implementation and preferences.
