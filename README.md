project Folder Structure

flask_mysql_project/
├── app.py
├── templates/
│   └── index.html



Project Title: Flask Frontend-Backend User Form

Description:

This is a simple full-stack web application that collects user data (name and email) via an HTML form and stores it in a MySQL database using a Flask backend. It's a basic example to demonstrate how a frontend communicates with a backend and a database.

Technologies used:
Frontend: HTML
Backend:Python (Flask)
Database: MySQL (MariaDB via XAMPP)

 Features

* Accepts user input via a form (`name` and `email`)
* Stores the data in a MySQL table named `users`
* Displays a thank-you message after submission
* Has a separate route `/users` to view all saved entries

---

 🚀 How to Run

1. Start MySQL using XAMPP Control Panel.
2. Import the SQL Dump:
   * Open `phpMyAdmin`
   * Create a database: `first_frontend_backend_connection`
   * Import `backup.sql` file
3. Run Flask App:

```bash
pip install flask pymysql
python app.py
```
4. Open browser:

   * Visit `http://127.0.0.1:5000` to view the form
   * Visit `http://127.0.0.1:5000/users` to see all saved users


 Database Table Structure (`users`)

| Column | Type        |
| ------ | ----------- |
| name   | VARCHAR(20) |
| email  | VARCHAR(20) |

 

