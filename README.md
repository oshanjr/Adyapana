
---

# Student Management System

A simple Java-based Student Management System designed to manage student records, including student information, attendance, and other key details for educational institutions. This project uses Java Swing for the graphical user interface (GUI) and MySQL for the database.

## Features
- **Student Registration**: Register students with their personal details.
- **Attendance Management**: Mark and manage student attendance.
- **Student Information**: View and edit student details.
- **Barcode Generation**: Each student has a unique ID with a barcode.
- **Student Search**: Search for students based on various criteria.
- **Backup and Restore**: Backup and restore database through a graphical interface.
- **User Authentication**: Admin login for secure access.

## Screenshots
(Provide a few screenshots of the application here, showing key features.)

## Tech Stack
- **Java**: For the backend logic and GUI using Swing.
- **MySQL**: For database management.
- **JDBC**: For connecting Java with MySQL database.
- **Barcode4J**: For generating student ID barcodes.

## Prerequisites
Before you begin, make sure you have the following installed:

- **Java JDK** (Version 8 or higher)
- **MySQL Database** and MySQL Workbench (or any MySQL client)
- **Barcode4J** (or ZXing for barcode generation)

## Getting Started

### 1. Clone the repository
Clone this repository to your local machine using the following command:

```bash
git clone https://github.com/your-username/Adyapana.git
```

### 2. Set up the database
Make sure to set up a MySQL database. You can create a database using the following SQL command:

```sql
CREATE DATABASE adyapana;
```

### 3. Configure database connection
In your project, open the database connection file (e.g., `DatabaseConnection.java`) and update the following fields:

- **URL**: The URL for your MySQL connection (e.g., `jdbc:mysql://localhost:3306/adyapana`).
- **USERNAME**: The MySQL username (e.g., `root`).
- **PASSWORD**: Your MySQL password.

### 4. Build and Run the Project

#### Using NetBeans IDE:
1. Open the project in **NetBeans**.
2. Build and run the project by clicking the **Run** button or press **F6**.

#### Using Command Line:
1. Navigate to your project directory.
2. Compile the project using `javac` or build using your preferred build tool (e.g., Maven or Gradle).
3. Run the compiled program:
```bash
java -jar adyapana.jar
```

### 5. User Authentication

- **Username**: `admin`
- **Password**: `admin`

The system requires an admin login for secure access to the management system.

### 6. Features
- **Student Registration**: The system allows for adding student details such as Name, Mobile, Email, etc.
- **Attendance**: You can mark attendance for students on a daily basis.
- **Barcode Generation**: A unique barcode is generated for each student, which can be scanned for easy identification.
- **Search**: Students can be searched by name or ID.
- **Backup/Restore**: The database can be backed up and restored using the system interface.

## Usage

1. **Register Students**: Add new students using the student registration form.
2. **Mark Attendance**: Select a student from the list and mark their attendance for the day.
3. **View/Edit Details**: Select any student and view/edit their personal details.
4. **Generate Barcode**: A barcode will be generated for each student, which can be printed or used for scanning.

## Contributing

Feel free to fork this project, create a branch, and submit pull requests for improvements or bug fixes. Please make sure to follow the existing code style.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- **Java**: Core programming language used for the application.
- **MySQL**: Database management system.
- **Barcode4J / ZXing**: Libraries used for barcode generation.
- **NetBeans**: Integrated Development Environment (IDE) used for development.

---


Let me know if you need further adjustments!
