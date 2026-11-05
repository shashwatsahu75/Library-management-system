# 📚 Library Management System

A console-based **Library Management System developed using C++** that simplifies library operations through Object-Oriented Programming (OOP). The application provides separate Admin and User interfaces to manage books, issue books, process returns, calculate rental charges, and handle overdue fines.

## 🚀 Features

### 🔐 Admin Module
- Secure admin login authentication.
- View all available books.
- Add new books to the library.
- Update admin username and password.
- Persistent storage of admin credentials.

### 👨‍🎓 User Module
- View the available book collection.
- Purchase/issue books for a specified duration.
- Check book availability.
- Return previously issued books.
- Automatic rental charge calculation.
- Late return fine calculation.

### 📖 Book Management
- Unique Book ID for every book.
- Store book title, author, price, and quantity.
- Track issued and available copies.
- Prevent issuing unavailable books.
- Save and retrieve book records using file handling.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| C++ | Core programming language |
| OOP | Application architecture |
| STL Vector | Managing book and issue records |
| File Handling | Persistent data storage |
| String & I/O | Input and output operations |
| GCC / G++ | Compilation |

## 🧠 OOP Concepts Implemented

- **Classes and Objects:** Used to represent books, users, administrators, and library operations.
- **Encapsulation:** Book and administrator data are managed through class members.
- **Inheritance:** The Admin class inherits from the Person class.
- **Abstraction:** Library operations are organized into dedicated member functions.

## 💰 Rental and Fine Calculation

The system uses the following fixed rates:

- **Rental Charge:** ₹10 per day.
- **Late Return Fine:** ₹15 per overdue day.

**Example:**

If a user issues a book for 5 days:

Rental = 5 × ₹10 = ₹50

If the book is returned after 7 days:

Late Fine = (7 − 5) × ₹15 = ₹30

## 📂 Project Structure

```text
Library-management-system/
│
├── Library management system.cpp
├── books.txt          # Generated book records
├── admin.txt          # Generated admin credentials
└── README.md
```

The `books.txt` and `admin.txt` files are generated and managed by the application.

## ⚙️ Installation and Execution

### 1. Clone the Repository

```bash
git clone https://github.com/shashwatsahu75/Library-management-system.git
```

### 2. Navigate to the Project Directory

```bash
cd Library-management-system
```

### 3. Compile the Program

```bash
g++ "Library management system.cpp" -o library
```

### 4. Run the Application

**Windows:**
```bash
library.exe
```

**Linux / macOS:**
```bash
./library
```

## 🔑 Default Admin Login

The application initializes with default administrator credentials.

For security reasons, credentials are not published in this README. Update the default credentials before deploying or sharing the application.

## 🔮 Future Enhancements

- Database integration using MySQL.
- Improved authentication and password encryption.
- Student/member registration.
- Book search functionality.
- Complete issue history and transaction records.
- GUI-based interface.
- Improved input validation and error handling.

## 👨‍💻 Developer

**Shashwat Sahu**

- GitHub: [@shashwatsahu75](https://github.com/shashwatsahu75)
- Project Repository: [Library Management System](https://github.com/shashwatsahu75/Library-management-system)

---

⭐ If you find this project useful, consider giving the repository a star!

*Developed with C++ and Object-Oriented Programming.*

