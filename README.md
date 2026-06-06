# Simple Bank System 🏦

A console-based banking application built in C++, where users can manage customer accounts through a simple interactive menu. The system supports deposits, withdrawals, account creation, deletion, and more — all stored in a local text file.

This is my second practical programming project in C++, built to apply real-world programming concepts in a structured and maintainable way.

---

## 🎓 Learning and Programming Foundation

This project was built as part of the practical applications in the **"Algorithms and Problem Solving - Level 3 (Course 7)"** course on [programmingadvices.com](https://programmingadvices.com), under the supervision of engineer **Mohammed Abu Hadhoud** 👑 ([LinkedIn](https://www.linkedin.com/in/abuhadhoud)).

This course deepened my understanding of file handling, data structures, and building menu-driven applications in C++.

---

## 🏧 How the System Works

The program launches a main menu with 7 options. The user navigates by entering a number, and each option leads to a dedicated screen. All client data is saved to and loaded from a local text file (`Clients.txt`), so data persists between runs.

---

## ✨ Key Features

| # | Feature | Description |
|---|---------|-------------|
| 1 | **View Client List** | Display all registered accounts with full details |
| 2 | **Add New Client** | Create a new bank account with PIN and balance |
| 3 | **Delete Client** | Safely remove an account from the system |
| 4 | **Update Client Info** | Modify customer details or balance |
| 5 | **Find Client** | Search for a client instantly by account number |
| 6 | **Transactions** | Deposit or withdraw funds with balance validation |
| 7 | **Exit** | Close the program |

---

## 🧠 Programming Concepts Applied

- **Structures** (`struct`) — to group all client data into a single model
- **Vectors** — to dynamically manage the client list in memory
- **File Handling** (`fstream`) — to store and retrieve client data from a text file
- **Functions** — to divide the code into small, independent, reusable units
- **Enums** (`enum`) — to manage menu options cleanly
- **Data Validation** — to prevent withdrawals exceeding available balance

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `bank.cpp` | The main source code written in C++ |
| `Clients.txt` | Auto-generated file that stores all client records |
| `README.md` | This file, explaining the project |

---

## 🛠 How to Run the Project

### Prerequisites
You need a C++ compiler installed (like **GCC** on Linux/Mac or **MinGW** on Windows).

### Steps

1. Clone this project:
```bash
git clone https://github.com/karimmesselmi/simple-bank-system.git
```

2. Go to the project folder:
```bash
cd simple-bank-system
```

3. Compile the code:
```bash
g++ bank.cpp -o BankSystem
```

4. Run the program:

On Windows:
```bash
BankSystem
```
On Linux/Mac:
```bash
./BankSystem
```

---

## 👤 About Me

**Karim Messelmi** — Computer Science student, building my foundation one project at a time.

🔗 [LinkedIn](https://www.linkedin.com/in/karim-messelmi-34a02a379)

> *"Every project I build teaches me something new. This is just the beginning of a long programming journey."* 🚀
