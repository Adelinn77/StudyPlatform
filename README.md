🎓 Study Platform
Welcome to the Study Platform repository! This project is a comprehensive educational management system designed to facilitate seamless interaction between students, teachers, and administrators.

📖 Project Overview
The Study Platform provides a centralized digital environment for academic institutions. It features role-based access control with dedicated dashboards and functionalities tailored 
to the specific needs of different users (Students, Teachers, and Admins). The platform streamlines day-to-day academic activities, from grading and scheduling to real-time communication.

For an in-depth look at the architecture, database schema, and detailed user flows, please refer to the included Documentation.pdf.

✨ Key Features
🔐 Role-Based Accounts
👨‍🎓 Students: Can view their grades, check their class schedules, join meetings, and communicate with peers/teachers.

👨‍🏫 Teachers: Can assign and manage grades, host meetings, set up their teaching schedule, and interact with students.

🛠️ Admins: Have full control over the platform, including user management, course creation, and system oversight.

🛠️ Core Functionalities
📊 Grading System: Teachers can seamlessly input grades, while students can track their academic performance in real-time.

📅 Schedule & Calendar: An integrated calendar system that displays class timetables, upcoming assignments, and important academic events.

📹 Meetings: Built-in support for scheduling and joining academic meetings or virtual classes.

💬 Real-Time Chat: A dedicated communication module allowing instant messaging between students and teachers to resolve queries quickly.

💻 Tech Stack
Core Language: Java

Database: SQL (Scripts provided in the SQL_Files directory)

Build Tool: Maven (pom.xml included)

IDE Compatibility: IntelliJ IDEA (ready-to-use .idea configuration)

📂 Repository Structure
src/ - Contains the Java source code for the application.

SQL_Files/ - SQL scripts for setting up the database schema and populating initial data.

pom.xml - Maven configuration file handling project dependencies.

Documentation.pdf - The complete official documentation of the project, including design details and functional requirements.

Assets (faculty.jpg, grinch.png, etc.) - Image and media assets used within the application UI.

🚀 Getting Started
Prerequisites
Java Development Kit (JDK): Version 11 or higher recommended.

Database: A local SQL server (e.g., MySQL) to run the database scripts.

Maven: To build the project and install dependencies.

IDE: IntelliJ IDEA, Eclipse, or your preferred Java IDE.

Installation & Setup
Clone the repository:

Bash
git clone https://github.com/Adelinn77/StudyPlatform.git
Set up the Database:

Open your SQL client.

Run the SQL scripts found in the SQL_Files/ folder to generate the required tables and initial mock data.

Update the database connection string in the project's configuration file (inside src/) to match your local database credentials.

Build the Project:

Open the project in your IDE.

Use Maven to resolve dependencies:

Bash
mvn clean install
Run the Application:

Execute the main application class to launch the platform.

📚 Documentation
For a complete understanding of how the application is built, including database relations, design patterns used, and usage scenarios, please read the Documentation.pdf provided in the root directory.
