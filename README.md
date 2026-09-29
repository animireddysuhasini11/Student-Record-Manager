🎓 Student Record Manager

A simple web-based Student Record Manager developed as part of the Module 2 Assignment.

📌 Project Description

The Student Record Manager allows users to add, validate, save, read, and manage student records through a simple and responsive web interface.

✨ Features

- ➕ Add Student
- 📧 Validate Email using Regular Expression (Regex)
- 💾 Save Student Data to JSON File
- 📂 Read Student Data from JSON File
- ⚠️ Handle Invalid Input using JavaScript Exceptions
- 🗑️ Delete Student Records
- 💻 Store data using Browser Local Storage
- 📱 Responsive design for desktop and mobile devices

🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Regular Expressions (Regex)
- Local Storage
- JSON
- GitHub Pages

📋 Student Details

The application stores the following information:

- Student Name
- Student ID
- Email
- Course

🔐 Validation

The application validates:

1. All required fields are filled.
2. Student name contains at least 2 characters.
3. Email address follows a valid email format using Regex.
4. Duplicate Student IDs are not allowed.
5. Imported JSON data is validated before loading.

⚠️ Exception Handling

JavaScript "try...catch" is used to handle invalid inputs and file-related errors.

Example:

try {
    // Validate and add student
}
catch (error) {
    // Display error message
}

💾 Data Storage

Student records are stored in the browser using Local Storage.

The application also provides:

- Save Data to File → Exports student records as a JSON file.
- Read Student Data → Imports student records from a JSON file.

🚀 How to Run

1. Download or clone this repository.
2. Open "index.html".
3. Open it in any modern web browser.
4. Add student details.
5. Click Add Student to create a record.

🌐 Live Demo

The project is deployed using GitHub Pages.

Live Website:
Add your GitHub Pages URL here after deployment.

Example:

"https://yourusername.github.io/student-record-manager/"

📁 Project Structure

Student-Record-Manager/
│
├── index.html
└── README.md

🎯 Assignment Requirements

Requirement| Implementation
Add Student| HTML Form + JavaScript
Validate Email| Regex
Save Data to File| JSON Export
Read Student Data| JSON Import
Handle Invalid Input| Try-Catch Exception Handling
Data Storage| Local Storage

👩‍💻 Author

Animireddy Suhasini

B.Tech Computer Science Student

---

⭐ Student Record Manager – Module 2 Assignment
