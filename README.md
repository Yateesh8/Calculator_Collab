# 🧮 Calculator_Collab

A simple Java-based console calculator built collaboratively by a team.  
It supports basic arithmetic operations: **Addition**, **Subtraction**, **Multiplication**, and **Division**, each implemented in separate files for modularity and teamwork.

---

## 📁 Project Structure

```
Calculator_Collab/
├── Add.java          // Contains method to add two numbers
├── Subtract.java     // Contains method to subtract two numbers
├── Multiply.java     // Contains method to multiply two numbers
├── Divide.java       // Contains method to divide two numbers
└── Calculator.java   // Main file that uses methods from all other files
```

---

## 👥 Team Collaboration Guidelines

- Each teammate is responsible for **one operation**.
- Do **not** overwrite each other’s files.
- Use **branches** for individual work, and create **pull requests** to merge.
- All logic should be in the respective class file (e.g., `Add.java` for addition).

---

## 🔧 How to Run

### 💻 1. Clone the Repo
```bash
git clone https://github.com/Yateesh8/Calculator_Collab.git
cd Calculator_Collab
```

### ⚙️ 2. Compile All Java Files
```bash
javac *.java
```

### 🚀 3. Run the Main Calculator
```bash
java Calculator
```

---

## 📌 Features

- Modular structure: each operation in a separate class
- Handles user input via console
- Includes division-by-zero check
- Easily extendable for more operations (e.g., modulus, power, etc.)

---

## 🧑‍💻 Contributors

| Name        | Operation        | File          |
|-------------|------------------|---------------|
| Yateesh    | Addition          | Add.java      |
| Naveen      | Subtraction       | Subtract.java |
| Himanshu    | Multiplication    | Multiply.java |
| Rameshwar   | Division          | Divide.java   |

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
