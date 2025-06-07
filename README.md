
# 📊 Stock Portfolio Management System

A **C++17-based console application** that enables investors and analysts to manage and monitor a portfolio of stocks and bonds. This open-ended academic project demonstrates advanced object-oriented programming techniques in C++.

---

## 🎯 Project Overview

This system simulates a **portfolio management environment**, offering a menu-driven interface for users to add, view, and sort stock and bond investments.

It showcases key C++ concepts including:

- Inheritance and polymorphism
- Exception handling
- Smart pointers
- Template functions
- Friend functions

The entire program is implemented in a single modular `.cpp` file with structured class definitions and clean memory-safe logic.

---

## 💡 Key Features

### 🧭 Interactive Console Interface
- Text-based input system for managing portfolio
- User prompts for adding, viewing, and sorting assets

### 🏛️ OOP Architecture
- Abstract base class `Stock`
- Derived classes: `Equity`, `Bond`
- `Portfolio` manages multiple stock types using polymorphism

### 🧠 Template-Based Entry
- Template method `createAndAddStock<T>()` handles all stock types
- Supports easy future expansion with minimal code repetition

### ♻️ Smart Memory Management
- Implements `shared_ptr` for safe dynamic memory allocation
- Avoids memory leaks and dangling references

### 🛑 Error Handling
- Graceful input validation using `InvalidStockException`
- Prevents app crashes due to invalid user inputs

### 🔍 Secure Data Access
- Friend function `showPortfolioDetails()` gives controlled access
- Does not violate encapsulation or OOP design principles

### 🎨 Enhanced User Experience
- Cleanly formatted output
- Border styles and section separation for readability

---

## ⚙️ Technologies & Concepts

| Tech / Concept     | Usage                                 |
|--------------------|----------------------------------------|
| `C++17`            | Core programming language              |
| `Smart Pointers`   | Memory safety                          |
| `Polymorphism`     | Interface implementation               |
| `Templates`        | Generic stock creation                 |
| `Exception Handling`| Robust error reporting                |
| `Friend Functions` | Secure portfolio access                |

---

## 🚀 Getting Started

### 🧰 Prerequisites

- Any C++17 compatible compiler (e.g., GCC, Clang, MSVC)
- Terminal or IDE like VS Code, CodeBlocks, CLion

### 🖥️ Compilation & Execution

```bash
# Step 1: Compile the program
g++ stock_market.cpp -o portfolio

# Step 2: Run the executable
./portfolio
````

---

## 📸 Sample Output

```text
<<<<<<<<<<<<<<<<<<<<< PORTFOLIO MANAGEMENT SYSTEM >>>>>>>>>>>>>>>>>>>>>>>>>>

Choose stock type to add (s: stock b: Bond): s
Enter Stock name: Infosys
Enter Stock price: 1520.45
Do you want to add another stock? (y/n): n

<<<<<<<<<<<<<< YOUR HOLDINGS >>>>>>>>>>>>>>>>>>
Stock: Infosys, Price: 1520.45
```

---

## 🔮 Future Improvements

* ✅ Add CSV/JSON export of holdings
* ✅ Filter & sort portfolio by category or price
* ⏳ Integrate real-time stock APIs for live updates
* 🌐 Migrate to a GUI interface using Qt
* 📈 Graph-based visualization of portfolio trends

---

## 🪪 License

Licensed under the **MIT License**
Feel free to use, modify, and share with proper attribution.

---

## 📬 Feedback & Contributions

We welcome suggestions and improvements!
Please create issues or pull requests to contribute.

---


