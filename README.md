# Automated Event Seating System

## Overview

This project focuses on developing an automated information system for generating seating plans at events like weddings, using a linear programming algorithm. The system replaces the traditional manual seating arrangement process, reducing time and effort while optimizing guest placement based on predefined constraints such as table capacity and guest preferences.

## Key Features

- **Automated Guest Seating**: Uses a linear programming algorithm to assign guests to tables efficiently.
- **Data Input and Categorization**: Users can input guest lists, categorize guests, and define constraints.
- **Optimization Algorithm**: Minimizes the number of tables used while maintaining guest preferences.
- **Real-Time Adjustments**: Allows users to modify guest lists and rerun the seating arrangement.
- **Data Export**: Enables downloading the seating plan as an Excel file.
- **User-Friendly Interface**: Designed with HTML, CSS, and JavaScript for a seamless experience.

## Technical Highlights

- **Backend**: Implemented in Python using the PuLP library for linear programming.
- **Frontend**: Web-based interface built with HTML, CSS, and JavaScript.
- **Database**: Uses SQL Server for storing guest information and seating arrangements.
- **Automation**: Algorithm optimizes seating and generates an interactive seating plan.
- **Performance Optimization**: Seating plan generated in under 2 minutes for large-scale events.

## How to Use

1. **Register/Login**: Create an account or log in to access the system.
2. **Upload Guest List**: Input guest details and categorize them.
3. **Define Constraints**: Set the maximum number of guests per table.
4. **Generate Seating Plan**: Click the button to run the algorithm.
5. **Review & Export**: View the optimized seating arrangement and download it as an Excel file.
6. **Make Adjustments**: Modify guest information and rerun the process if needed.

## Requirements

- Web browser (Google Chrome, Firefox, Edge recommended)
- Internet connection
- SQL Server for database management
- Python with the following libraries:
    - flask
    - pyodbc
    - bcrypt
    - pulp
    - threading
    - io
    - os
    - openpyxl
    - pandas

## Authors

- **Chen Biazi**
- **Noa Ezri**
- **Niv Meirovitz**
- **Alon Achituv**

## Acknowledgments

- Supervised by Dr. Gabi Pinto
- Developed as part of the *Analysis and Planning of Information Systems A* course

## Future Enhancements

- **Mobile App Integration**: Expanding functionality for mobile users.
- **Multiple Event Management**: Allowing users to manage multiple seating plans.
- **Guest Confirmation System**: Integrating RSVP tracking to adjust seating dynamically.
- **AI-based Guest Arrangement**: Enhancing the algorithm to factor in social relationships for optimal guest experience.

This system significantly reduces the complexity of event planning by automating the seating arrangement process, improving efficiency, and ensuring guest satisfaction.

