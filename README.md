

  
  
# Employee Tracker

## Description
The Employee Tracker is a comprehensive management system designed to handle employee-related data in a business. This project leverages PostgreSQL and Inquirer to provide an interactive and user-friendly interface for managing employees, departments, and roles.


## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Tests](#tests)
- [Questions](#questions)

## Video
- [Google Drive Link](https://drive.google.com/file/d/1GJkKIYCHQ-P-Nxiikm-yoqPOQH9OrGuz/view)

## Features

- **View**: Display all departments, roles, and employees.
- **Add**: Insert new departments, roles, and employees into the database.
- **Update**: Modify employee roles as needed.
- **Interactive CLI**: User-friendly command-line prompts for easy data management.


## Installation

To set up the Employee Tracker on your local machine, follow these steps:

1. **Clone the Repository:**
   - Open a terminal and run:
     ```bash
     git clone <repository-url>
     ```
   - Replace `<repository-url>` with the URL of your Git repository.

2. **Navigate to the Project Directory:**
   - Change into the project directory:
     ```bash
     cd <project-directory>
     ```
   - Replace `<project-directory>` with the name of your project folder.

3. **Install Dependencies:**
   - Ensure you have [Node.js](https://nodejs.org/) installed.
   - Install the required npm packages by running:
     ```bash
     npm install
     ```
   - This command will install all dependencies listed in the `package.json` file, including `pg`, `inquirer`, and `express`.

4. **Set Up the Database:**
   - Ensure PostgreSQL is installed and running on your machine.
   - Apply the database schema and seed data:
     - Run the schema SQL file to create the necessary tables:
       ```bash
       \i schema.sql
       ```
     - Run the seeds SQL file to create the necessary tables:
       ```bash
       \i seeds.sql
       ```

5. **Run the Application:**
   - Start the application with:
     ```bash
     npm start
     ```
   - This command will launch the application and display the main menu for managing employee data.

6. **Optional - Update Environment Variables:**
   - If needed, update the database connection settings in the `connections.js` file to match your PostgreSQL configuration.

By following these steps, you'll have the Employee Tracker application set up and ready for use on your local machine.


## Usage
Use this application to efficiently manage your company’s employee information, track roles and departments, and keep your organizational data up-to-date.


## Tests
There are no tests at this time.

## Questions
If you have any questions, please reach out to me:
- Github [Vtencouchclimbr](https://github.com/Vtencouchclimbr)
- Email: LmntryLmnt@gmail.com
  