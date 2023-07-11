# Workout Manager
### Introduction
Workout Manager is a web application that allows users to create, record, and view their daily workout records. It provides a simple and powerful tool to track workouts and monitor progress.

## Project Description

The purpose of Workout Manager is to help users maintain a log of their workouts in a convenient and organized manner. The key features of the application include:

- Record Creation: Users can log their workout details by selecting the date from a date picker, choosing the workout type from a dropdown menu (e.g. bench press, shoulder press), and inputting the number of sets, weight in kilograms, and repetitions performed.
- Record Viewing: Users can easily view their workout records for a specific date by selecting the desired date. This allows them to track their progress over time and analyze their workout patterns.
- Simplicity and User-Friendliness: The application is designed to be intuitive and user-friendly, allowing users to quickly record their workouts without any unnecessary complexity.

Workout Manager aims to provide a streamlined and efficient solution for individuals who want to keep track of their exercise routines and monitor their fitness journey.

## Features

- Record Creation: Users can log the date, workout type, number of sets, weight, and repetitions for each exercise.
- Record Viewing: Users can view their workout records for a specific date, allowing them to review their progress and track their performance over time.
- User-Friendly Interface: The application offers an intuitive and straightforward user interface, making it easy for users to navigate and interact with the system.
- Date Picker: Users can conveniently select dates using a date picker to log or view their workout records.

### Database Setup

- **Step 1**: Copy the provided `capstone_database.sql` file to a convenient location.
- **Step 2**: Open Command Prompt and start the MariaDB server (ensure that MariaDB 10.6 is installed).
- **Step 3**: In Command Prompt, navigate to the directory where the MariaDB `bin` folder is located.
- **Step 4**: Move the `capstone_database.sql` file into the MariaDB `bin` folder.
- **Step 5**: In Command Prompt, run the following command to import the SQL file and populate the database:
   ```
   mysql -u username -p capstone < capstone_database.sql
   ```
   Replace `username` with your MariaDB username.
- **Step 6**: The data will be successfully populated in the database.

### Application Startup

- **Step 1**: Open IntelliJ IDE.
- **Step 2**: Run the backend server.
- **Step 3**: Open Visual Studio Code (VS Code).
- **Step 4**: In the VS Code terminal, navigate to the directory where the React project is located.
- **Step 5**: Run the following command to install the necessary dependencies: `npm install`
- **Step 6**: Once the installation is complete, start the frontend development server: `npm start`

### Usage

- **Step 1**: Launch the application in your browser at `http://localhost:3000` or `http://localhost:3000/home`.
- **Step 2**: Use the navigation bar or enter specific URLs to perform actions:
   - To create a new record: `http://localhost:3000/createRecord`
   - To view records: `http://localhost:3000/viewRecords`

## Credits

Workout Manager utilizes the following technologies, libraries, and frameworks:

- React (Functional Components): A JavaScript library for building user interfaces.
- Spring Boot: A Java framework used for building robust and scalable web applications.
- MariaDB: An open-source relational database management system used for storing and managing the workout records.
- Bootstrap: A popular CSS framework that provides pre-styled components and responsive design for a visually appealing user interface.
- Logo Image: The logo image used in Workout Manager was sourced from [Flaticon](https://www.flaticon.com/free-icons/gym/2).
