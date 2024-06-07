# Hospital System Application
This project is a graphical user interface (GUI) application built using Python's Tkinter library to interact with a MySQL database for managing hospital records. The application allows users to view, insert, and delete entries in different tables within the database. Here's a breakdown of the key components and functionalities:
Viewing Data: Users can click buttons corresponding to different tables (Doctor, Hospital, Patient, MedicalRecord) to view their data. The Listbox is populated with the data from the selected table, and Entry widgets are created for data insertion.
Inserting Data: Users can enter new data in the Entry widgets and press the Enter button. The insert function collects the data and inserts it into the corresponding table in the database.
Deleting Data: Users can select an entry in the Listbox and press the Delete key. The remove_entry function deletes the selected entry from the corresponding table in the database. This project provides a simple yet functional interface for managing hospital records in a MySQL database, allowing for basic CRUD (Create, Read, Update, Delete) operations.
This project aims to streamline the process of managing hospital data, reducing administrative burden and improving data accuracy and accessibility.

## Setup Instructions
1. Install MySQL Server
 * Download MySQL Server.
 * Go to the MySQL Downloads page and download the MySQL installer for Windows.
 * Run the installer and follow the setup instructions, choosing the default options unless you have specific requirements.
2. Configure MySQL Server:
 * During installation, set up a root password and remember it for later use.
 * Complete the installation and start the MySQL server.
3. Install Python:
 * Download and install Python from the official Python website.
4. Install MySQL Connector for Python:
 * Open a terminal in VS Code (Ctrl+ `) and run the following command to install the MySQL connector: pip install pymysql
   

