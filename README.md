# 📚 The Book Borrower

A full-stack web application for managing book borrowing and user exchanges, with focus on backend development, database design, and real-world application logic.


## 📑 Table of Contents

- [🧾 Description](#description)
- [✨ Features](#features)
- [🏗️ Architecture & Design](#architecture--design)
- [🗄️ Database](#database)
- [💻 Technologies](#technologies)
- [⚙️ Installation](#installation)
- [▶️ Usage](#usage)
- [🔑 Demo Credentials](#demo-credentials)
- [📷 Screenshots](#screenshots)
- [🎯 Purpose](#purpose)
- [📚 Key Learnings](#key-learnings)
- [⚠️ Known Limitations](#known-limitations)
- [🔗 Future Improvements](#future-improvements)
- [👩‍💻 Author](#author)

## 🧾 Description

This project was developed as a portfolio application to simulate a real-world library system on a smaller scale.

It allows users to share books, borrow from others, and track exchanges, with a focus on backend development, database design, and application logic.


## ✨ Features

- User registration and authentication  
- Add, edit, and delete books (admin role)  
- Browse available books  
- Borrow and return books  
- Track currently borrowed books  
- User profile management  


## 🏗️ Architecture & Design

The application follows a structured approach:

- **Presentation Layer** – ASP.NET Web Forms UI  
- **Business Logic Layer** – borrowing workflows and rules  
- **Data Access Layer** – SQL Server database interaction  

This separation improves maintainability and clarity of the application.


## 🗄️ Database

- Built using SQL Server  
- Stores users, books, and borrowing records  
- Supports relational data and borrowing workflows  
- Handles CRUD operations and data consistency  


## 💻 Technologies

- **Backend:** C#, .NET Framework, ASP.NET Web Forms  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** SQL Server  
- **Tools:** Visual Studio  


## ⚙️ Installation

1. Clone or download the repository  

```bash
git clone https://github.com/kristinavic/The-book-borrower.git
```

2. Open the solution Izposoja.sln in Visual Studio

3. Configure the database:
- Open Server Explorer → Add Connection
- Select Microsoft SQL Server Database File (SqlClient)
- Choose Microsoft SqlClient Data Provider
- Locate and connect to the Library.mdf file
- Copy the generated connection string

4. Update the connection string in Web.config:
```xml
<connectionStrings>
  <add name="dbcon"
       connectionString="Data Source=(LocalDB)\MSSQLLocalDB;AttachDbFilename=YOUR_CONNECTION_STRING_HERE;Integrated Security=True;Connect Timeout=30"
       providerName="Microsoft.Data.SqlClient" />
</connectionStrings>
```


## ▶️ Usage

- Log in using provided credentials  
- Browse and search available books  
- Borrow books from other users  
- Return borrowed books  
- Track borrowing activity  
- Admin users can manage books and users  


## 🔑 Demo Credentials

**Admin**
- Username: admin
- Password: admin

**Users**
- coconut / cococatherine
- thebuilder / letsbuild0
- king / longlivetheking1


## 📷 Screenshots
📌 These screenshots show the main functionality of the application.

### 📚 App overview
![Books](./screenshots/index.png)

### ➕ Add book
![Add book](./screenshots/add-book.png)

### 🔄 Borrow system
![Borrow](./screenshots/borrow.png)

### 👤 User profile
![Profile](./screenshots/profile.png)


## 🎯 Purpose

This project was built to strengthen my skills in backend development, database design, and implementing real-world application logic.

It represents my transition into software development and my focus on building data-driven applications.


## 📚 Key Learnings

- Designing and working with relational databases (SQL Server)
- Implementing business logic for real-world workflows
- Handling user interactions in ASP.NET Web Forms
- Managing data flow between UI and database


## ⚠️ Known Limitations

- Borrowing requires knowing other users’ usernames
- Limited data visibility control for users
- Users cannot fully track books they have borrowed


## 🔗 Future Improvements
- Improve user visibility and privacy
- Enhance borrowing workflow and UX
- Add better tracking of borrowed books
- Modernize architecture (e.g. API-based backend)


## 👩‍💻 Author

Kristina Vičič

GitHub: https://github.com/kristinavic

LinkedIn: https://linkedin.com/in/kristinavicic

