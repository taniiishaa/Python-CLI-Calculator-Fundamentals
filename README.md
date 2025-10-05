# 🧮 Python-CLI-Calculator-Fundamentals

A robust and user-friendly **Command-Line Interface (CLI) Calculator** built entirely with Python.

This project was developed as a foundational exercise to solidify core Python programming principles, focusing on **modular architecture, effective error handling, and building a persistent, interactive application session.**

## ✨ Key Features

* **Clean and Modular Code:** Arithmetic operations (add, subtract, multiply, divide) are encapsulated in separate functions, promoting **readability and reusability**.
* **Robust Error Handling:** Implements **`try-except` blocks** to gracefully manage:
    * **`ValueError`**: Catches non-numeric input from the user.
    * **`ZeroDivisionError`**: A specific safeguard is implemented in the `divide` function to prevent application crashes.
* **Persistent Session:** The application runs in a continuous `while` loop, allowing for multiple, seamless calculations without needing a restart.
* **User-Controlled Exit:** Users can terminate the program easily at any time by typing `exit`.
* **Intuitive CLI:** Guides the user with clear prompts for operation selection and numerical input.

## 🚀 Getting Started

Follow these steps to clone the repository and run the calculator on your local machine.

### Prerequisites

* Python 3.x installed on your system.

### Installation & Execution

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/Python-CLI-Calculator-Fundamentals.git](https://github.com/YOUR_USERNAME/Python-CLI-Calculator-Fundamentals.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd Python-CLI-Calculator-Fundamentals
    ```

3.  **Run the calculator script:**
    ```bash
    python calculator.py
    ```

## 🛠️ Development Process Summary

This project guided me through a complete, professional development cycle:

1.  **Architecture:** Defined core functions (`add`, `subtract`, `multiply`, `divide`) for a highly **modular and reusable codebase**.
2.  **Core Logic:** Built the main application using a **persistent `while` loop** and **conditional logic** to manage the interactive session and operation routing.
3.  **Defensive Programming:** Integrated robust **exception handling** to ensure application stability against invalid inputs (`ValueError`) and critical runtime issues (`ZeroDivisionError`).
4.  **Version Control:** Managed the codebase using Git and deployed the final product to GitHub, demonstrating proficiency in standard **development and deployment workflows**.

---
