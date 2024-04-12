# Bike Rental Shop Script

This Bash script implements a simple bike rental shop management system. Users can rent bikes, return bikes, and exit the program.

## Features

- **Rent a Bike**: Allows users to rent a bike by selecting from available options and providing their phone number and name.
- **Return a Bike**: Allows users to return a rented bike by selecting from their rented bikes and confirming the return.
- **Database Interaction**: Utilizes PostgreSQL to interact with a database named "bikes" containing tables for bikes, customers, and rentals.
- **User Input Handling**: Handles user input validation and error messages for smooth user interaction.
- **Main Menu Navigation**: Provides a main menu with options to rent a bike, return a bike, or exit the program.

## Technology Stack

- **Bash Scripting**: The script is written in Bash, a Unix shell and command language.
- **PostgreSQL**: The database management system used for storing bike, customer, and rental information.
- **SQL**: Structured Query Language is used to interact with the PostgreSQL database.
- **Terminal Interaction**: Users interact with the script through the terminal interface.

## Usage

1. **Database Setup**: Log in to psql with `psql --username=freecodecamp --dbname=postgres` and create a database named "bikes" with `CREATE DATABASE bikes;`.
2. **Table Creation**: Create tables for bikes, customers, and rentals in the "bikes" database.
3. **Run the Script**: Execute the Bash script by running `./bikes.sh` in the terminal.
4. **Main Menu**: Choose from options to rent a bike, return a bike, or exit the program.
5. **Follow Prompts**: Follow the prompts to rent or return bikes as needed, providing necessary information such as phone number and bike selection.
6. **Exit**: Choose the "Exit" option from the main menu to terminate the program.

## Example

Here's an example scenario of using the bike rental shop script:

1. User runs the script and sees the main menu.
2. User selects the option to rent a bike.
3. User chooses from available bikes and provides their phone number and name.
4. User confirms the rental and receives a confirmation message.
5. User later returns the rented bike using the script.
6. User selects the option to return a bike, chooses the bike to return, and confirms the return.
7. User receives a thank you message for returning the bike.
