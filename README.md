# Bash-DBMS

A simple Database Management System (DBMS) implemented using Bash scripting. This project allows users to perform basic database operations such as creating and deleting databases and tables, as well as inserting, updating, and deleting records.

## Features

- **Database Operations:**
  - Create and delete databases.
  - List existing databases.
  - Connect to a selected database.

- **Table Operations:**
  - Create and drop tables within a connected database.
  - List tables in the current database.

- **Record Operations:**
  - Insert new records into tables.
  - Update existing records.
  - Delete records from tables.
  - Select and display records based on specific criteria.

## Prerequisites

Ensure that you have Bash installed on your system. This script is compatible with Unix-like operating systems that support Bash.

## Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/khaled-101/Bash-DBMS.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd Bash-DBMS
   ```

3. **Run the Main Script:**

   ```bash
   bash DBMENU
   ```

   This will launch the main menu of the DBMS, where you can choose various operations to perform.

## Usage

Upon running the `DBMENU` script, you'll be presented with a menu-driven interface that guides you through various database operations. Follow the on-screen prompts to create databases, manage tables, and manipulate records.

## Project Structure

The repository contains the following scripts:

- **DBMENU**: Main menu script that serves as the entry point to the DBMS.
- **CreateDB**: Script to create new databases.
- **DropDB**: Script to delete existing databases.
- **ListDB**: Script to list all available databases.
- **ConnectDB**: Script to connect to a selected database.
- **Create_Table**: Script to create new tables within a connected database.
- **Drop_Table**: Script to delete tables from the current database.
- **List_Tables**: Script to list all tables in the current database.
- **Table_menu**: Script that provides a menu for table-related operations.
- **reusable**: Contains reusable functions used across multiple scripts.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.

## Acknowledgments

This project is inspired by various Bash scripting DBMS implementations and serves as a learning tool for shell scripting and basic database management concepts.

