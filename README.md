# 📚 Library Management System (LMS)

A professional, console-based Library Management System built with C++. This project demonstrates core Object-Oriented Programming (OOP) concepts such as classes, encapsulation, and basic data management.

---

## 🚀 Features

- **User Authentication**: Secure login system with administrative access.
- **Book Management**:
  - View a comprehensive list of available books.
  - Search for books by **Title**, **Author**, or **ISBN**.
- **Borrowing System**: Real-time stock management when books are borrowed.
- **Return & Fine System**: 
  - Automated return tracking.
  - Logical fine calculation (₹500) for late submissions (returns after the 12th).
- **Interactive CLI**: ASCII art-enhanced interface for a better user experience.

---

## 🛠️ Installation & Setup

### Prerequisites
- A C++ compiler (e.g., GCC, Clang, or MSVC).
- A terminal or command prompt.

### Compilation
Clone the repository and compile the source file using your preferred compiler:

```bash
g++ lms.cpp -o lms
```

### Running the Application
After compilation, run the executable:

```bash
./lms
```

---

## 📖 Usage Guide

### Default Credentials
To access the system, use the following default login credentials:

| Username | Password |
| :--- | :--- |
| `Hasaan` | `123` |

### Workflow
1. **Launch**: Start the program to see the LMS logo.
2. **Authenticate**: Register (demo) or Login using the credentials above.
3. **Main Menu**: Choose from options to view, search, borrow, or return books.
4. **Exit**: Terminate the session safely.

---

## 📂 Repository Structure

- `lms.cpp`: The main C++ source code containing all logic and UI.
- `LICENSE`: MIT License.

---


## ⚖️ License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
