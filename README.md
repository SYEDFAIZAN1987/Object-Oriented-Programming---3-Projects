# 🏥 Electronic Health Record (EHR) System – Object-Oriented Python Project - 1

This project implements a simplified **Electronic Health Record (EHR) system** using **Object-Oriented Programming (OOP)** principles in Python. It is designed as a portfolio piece to demonstrate solid understanding of OOP concepts like encapsulation, inheritance, polymorphism, and object relationships in a real-world healthcare context.

---

## 🚀 Features

- **Patient and Doctor Records**: Create and manage profiles for patients and doctors.
- **Clinical Visits**: Record doctor-patient visits with dates and medical reasons.
- **Diagnoses & Prescriptions**: Add diagnoses and prescribe multiple medications during visits.
- **Medical History Tracking**: Maintain a running medical history for each patient.
- **Age Calculation**: Automatically compute age from date of birth using Python’s datetime module.

---

## 🧱 Object-Oriented Design

| Class        | Description |
|--------------|-------------|
| `Person`     | Base class for both `Patient` and `Doctor` |
| `Patient`    | Inherits from `Person`, adds medical history and visit records |
| `Doctor`     | Inherits from `Person`, includes doctor ID and specialty |
| `Visit`      | Links patient, doctor, visit date, reason, diagnosis, and prescriptions |
| `Prescription` | Represents prescribed medication, dosage, and duration |

---

## 📁 Project Structure

```
EHR_OOP_Portfolio_Project/
├── EHR_OOP_Portfolio_Project.ipynb    # Main Jupyter notebook with code and explanations
├── README.md                          # Project overview and documentation
```

## 🛠️ Technologies Used

- Python 3.x  
- Jupyter Notebook  
- `datetime` module  
- Markdown for documentation  

## 📸 Sample Output

```
Patient: John Doe, ID: P1234, Age: 35  
Visit on 2025-04-11 - Reason: Chest pain, Doctor: Alice Smith  
Diagnosis: Angina  
Prescriptions:  
 - Aspirin 75mg, once daily for 30 days  
 - Nitroglycerin 0.4mg, as needed for as needed  
```

## 🎯 Learning Objectives

✅ Reinforce foundational OOP design patterns  
✅ Apply Python classes in a real-world domain (healthcare)  
✅ Simulate data interaction between linked objects (Patient ↔ Visit ↔ Doctor)  
✅ Build a clean, extensible, and maintainable codebase  

## 📚 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ehr-oop-system.git
   cd ehr-oop-system
   ```

2. Launch the Jupyter notebook:
   ```bash
   jupyter notebook EHR_OOP_Portfolio_Project.ipynb
   ```

3. Run all cells and view outputs inline.

## 👨‍⚕️ Author

**Syed Faizan, MD**  
Master’s in Data Analytics and Applied Machine Learning  
📫 [syedfaizaan.com](https://syedfaizaan.com) | [LinkedIn](https://linkedin.com/in/drsyedfaizanmd)

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

# 📦 Data Structures from Scratch – Object-Oriented Python Projects - 2 and 3

This repository contains implementations of core **data structures** using **Object-Oriented Programming (OOP)** principles in Python. These projects are designed to reinforce foundational concepts of data abstraction, encapsulation, dynamic resizing, and interface design.

The notebook contains two main data structures:
- `CustomList`: A dynamic array implementation similar to Python’s built-in list.
- `ComplexNumber`: A class to represent and manipulate complex numbers with arithmetic operations.

---

## 📁 Project Structure

```
DataStructuresFromScratch/
├── DataStructuresFromScratch.ipynb   # Jupyter notebook with full implementations and tests
├── README.md                         # This file
```

---

## 🧠 Implemented Data Structures

### 1. `CustomList`

A dynamic array class that mimics Python’s native list functionality. Built using `ctypes` for low-level memory control.

**Key Features:**
- Dynamic resizing (doubling capacity)
- `append()`, `pop()`, `insert()`, `remove()` methods
- Index-based access via `__getitem__`
- Printable representation via `__str__`
- Capacity vs. size tracking
- Error handling for invalid operations

### 2. `ComplexNumber`

A class to model and perform operations on complex numbers.

**Key Features:**
- Constructor with real and imaginary components
- Addition, subtraction, multiplication operations
- Equality checks with `__eq__`
- Proper formatting via `__str__`

---

## 🛠️ Technologies Used

- Python 3.x  
- Jupyter Notebook  
- `ctypes` for memory-based array control  
- Object-Oriented design patterns  

---

## 📸 Sample Output

```
[1, 2, 3, 4]
Popped: 4
After remove(2): [1, 3]

Complex Numbers:
c1 = 3 + 2i
c2 = 1 + 7i
Addition: 4 + 9i
Multiplication: -11 + 23i
```

---

## 🎯 Learning Objectives

✅ Understand how dynamic arrays work internally  
✅ Apply low-level memory concepts using `ctypes`  
✅ Design reusable, extensible class-based data structures  
✅ Reinforce operator overloading and method encapsulation  

---

## 📚 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/data-structures-oop.git
   cd data-structures-oop
   ```

2. Launch the Jupyter notebook:
   ```bash
   jupyter notebook DataStructuresFromScratch.ipynb
   ```

3. Run the cells to test both `CustomList` and `ComplexNumber` implementations.

---

## 👨‍💻 Author

**Syed Faizan, MD**  
Master’s in Data Analytics and Applied Machine Learning  
📫 [syedfaizaan.com](https://syedfaizaan.com) | [LinkedIn](https://linkedin.com/in/drsyedfaizanmd)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

