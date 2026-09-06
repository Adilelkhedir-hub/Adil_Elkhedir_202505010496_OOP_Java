# BIT1123 Object-Oriented Programming (Java)


> A collection of Java tutorial exercises completed throughout the **BIT1123 Object-Oriented Programming** course. This repository demonstrates the development of fundamental Java and Object-Oriented Programming skills from basic syntax to inheritance, abstraction, file handling, and a simple GUI application.

---

## Assignment Information

| Item | Details |
|---|---|
| **Assignment** | Assignment 1 – Individual |
| **Course** | BIT1123 Object-Oriented Programming |
| **Student** | Adil Elkhedir |
| **Student ID** | 202505010496 |
| **University** | City University Malaysia |
| **Campus** | Cyberjaya Campus |
| **Repository** | `Adil_Elkhedir_202505010496_OOP_Java` |
| **GitHub URL** | https://github.com/Adilelkhedir-hub/Adil_Elkhedir_202505010496_OOP_Java |

---

## 📚 Course Overview

This repository was created to organize the practical Java work completed during the Object-Oriented Programming course.

The tutorials focus on building programming fundamentals and gradually introducing Object-Oriented Programming concepts such as:

- Classes and objects
- Constructors
- Attributes and methods
- Encapsulation
- Getters and setters
- Inheritance
- Method overriding
- Abstraction
- File input and output
- Exception handling
- Java Swing GUI development
- Event-driven programming

The repository also demonstrates the use of GitHub as a central location for managing source code, supporting files, and assignment documentation.

---

## 🗂️ Repository Structure

```text
Adil_Elkhedir_202505010496_OOP_Java/
│
├── README.md
├── LICENSE
├── myreport.pdf
├── student.java
│
├── week_1/
│   ├── Hello.java
│   └── StudentGrade.java
│
├── week_2/
│   ├── Main.java
│   └── Student.java
│
├── week3/
│   ├── person.java
│   ├── student.java
│   ├── lecturer.java
│   └── main.java
│
├── week_5/
│   ├── Main.java
│   ├── Student.java
│   └── document.txt
│
├── week_6/
│   ├── Employee.java
│   ├── Lecturer.java
│   └── Main.java
│
├── week_7/
│   ├── Appliance.java
│   ├── Refrigerator.java
│   ├── WashingMachine.java
│   └── Main.java
│
├── week8&9/
│   └── week8.java
│
└── week_10/
    ├── Questions.java
    └── QuizBattleGUI.java
```

> **Note:** The current repository uses the folder names and naming conventions shown above. Week 4 does not currently appear as a separate folder, while Week 8 and Week 9 are combined into `week8&9`.

---

## 🧪 Tutorial Summary

### Week 1 — Java Basics

The first tutorial introduces basic Java programming and program execution.

**Examples:**
- `Hello.java` – prints a simple welcome message.
- `StudentGrade.java` – accepts a student's score and determines a grade using conditional statements and `Scanner` input.

**Main concepts:**
`main()` method, output, variables, user input, `if / else if / else`, data types, and basic program flow.

---

### Week 2 — Classes, Objects and Methods

Week 2 moves from basic Java syntax toward object-oriented programming.

The `Student` class stores student information such as ID, name, age, and GPA. The `Main` class creates a `Student` object and calls methods to display information and simulate student activities.

**Main concepts:**
- Classes
- Objects
- Attributes
- Constructors
- Methods
- Object creation using `new`

---

### Week 3&4 — Inheritance and Method Overriding

This tutorial introduces relationships between classes using inheritance.

The `person` class acts as a parent class, while `Student` and `lecturer` extend it. The child classes override the `introduce()` method to provide their own behavior.

**Main concepts:**
- Inheritance
- Parent and child classes
- `extends`
- `super`
- Encapsulation through private fields
- Getters
- Method overriding
- Polymorphic behavior

---

### Week 5 — Encapsulation

Week 5 focuses on protecting object data by using private attributes and public getter/setter methods.

The `Student` class contains private fields for student ID, name, CGPA, and programme. These values are accessed and updated through methods such as `setName()`, `getName()`, `setCGPA()`, and `getCGPA()`.

**Main concepts:**
- Encapsulation
- Access modifiers
- `private`
- Getter methods
- Setter methods
- Data protection

---

### Week 6 — Inheritance with Employee and Lecturer

Week 6 applies inheritance to a simple employee hierarchy.

`Lecturer` extends `Employee` and reuses inherited employee information while adding lecturer-specific information such as subject and department.

**Main concepts:**
- Inheritance
- Code reuse
- `protected` members
- Constructors
- `super()`
- Reusing parent-class methods

---

### Week 7 — Abstraction

Week 7 introduces abstraction through an abstract `Appliance` class.

The repository includes `Refrigerator` and `WashingMachine` subclasses, each implementing its own version of the abstract `operate()` method.

**Main concepts:**
- Abstract classes
- Abstract methods
- Method implementation in subclasses
- Inheritance
- Common behavior and specialized behavior

---

### Week 8 & 9 — ArrayList and File Handling

The Week 8 & 9 exercise develops a small task-management program.

The program accepts three tasks from the user, stores them in an `ArrayList`, displays them, writes them to a text file, and then reads the saved tasks back from the file.

**Main concepts:**
- `ArrayList`
- `Scanner`
- File writing with `FileWriter`
- File reading with `File` and `Scanner`
- `try-with-resources`
- Exception handling
- `IOException`
- `FileNotFoundException`

---

### Week 10 — Java Swing GUI

The final tutorial demonstrates a simple graphical user interface called **Programming Quiz Battle**.

The application displays a question with two answer buttons. When the user selects an answer, an event handler checks the selected option and displays either a correct or incorrect result.

The GUI is implemented using Java Swing components such as `JFrame`, `JLabel`, and `JButton`.

**Main concepts:**
- Java Swing
- GUI components
- `JFrame`
- `JLabel`
- `JButton`
- `ActionListener`
- Event-driven programming
- Object interaction

---

## 🛠️ Technologies Used

- **Java** – Main programming language
- **Java Standard Library** – Core Java classes and APIs
- **Java Swing** – GUI development
- **ArrayList** – Dynamic collection of tasks
- **File I/O** – Reading and writing text files
- **Git** – Version control
- **GitHub** – Repository hosting and project documentation

---

## ▶️ How to Run the Projects

### Requirements

Install the following before running the Java files:

1. **Java Development Kit (JDK)**
2. A Java-compatible IDE or code editor, such as:
   - IntelliJ IDEA
   - Eclipse
   - Visual Studio Code with Java extensions

### Run a Simple Program

Open a terminal in the folder containing the Java file and compile it:

```bash
javac Hello.java
```

Then run the compiled class:

```bash
java Hello
```

### Run a Program with Multiple Classes

For example, Week 2 contains `Main.java` and `Student.java`:

```bash
cd week_2
javac *.java
java Main
```

### Run Week 10 GUI

The Week 10 application can be compiled and executed with:

```bash
cd week_10
javac *.java
java QuizBattleGUI
```

A graphical quiz window should open after the program starts.

> **Tip:** When running the Week 8 & 9 task program, the application writes the entered tasks to `task.txt` in the program's working directory.

---

## 🎯 Learning Outcomes Demonstrated

By organizing the tutorial work into this repository, the following programming skills are demonstrated:

| Skill | Evidence in Repository |
|---|---|
| Java fundamentals | Week 1 |
| User input and conditional logic | Week 1 |
| Classes and objects | Week 2 |
| Constructors and methods | Week 2 |
| Inheritance | Week 3, Week 6, Week 7 |
| Encapsulation | Week 3, Week 5 |
| Method overriding | Week 3 |
| Abstraction | Week 7 |
| Collections | Week 8 & 9 |
| File handling | Week 8 & 9 |
| Exception handling | Week 8 & 9 |
| GUI development | Week 10 |
| Event handling | Week 10 |

---

## 📄 Assignment Report

The assignment requires the self-reflective report to be uploaded to the repository as `myreport.pdf`. Add the completed report to the repository root before final submission.

The report covers the learning experience, challenges encountered, solutions used, Java programming development, understanding of OOP concepts, and future learning plans.

---

## 💡 Reflection Summary

Working through these tutorials helped build a stronger understanding of Java programming step by step. The early exercises focused on Java syntax, input, conditions, classes, and objects, while later tutorials introduced more important OOP concepts such as encapsulation, inheritance, and abstraction.

One of the main improvements was learning how different classes can work together instead of writing everything inside one program. File handling and GUI development also provided practical experience beyond basic console applications.

The most challenging areas were understanding how classes are related, using inheritance correctly, and managing file input/output and exceptions. These challenges were addressed through repeated practice, testing the programs, checking compilation errors, and studying how each part of the code interacts with the others.

The next step is to improve code quality, naming consistency, validation, exception handling, and GUI design while developing larger Java applications using stronger OOP principles.

---

## 🚀 Future Improvements

Possible improvements for this repository include:

- Add the missing Week 4 tutorial files.
- Standardize folder names (`week1`, `week2`, etc.) across all tutorials.
- Improve Java class and file naming consistency.
- Add more detailed comments and documentation to selected programs.
- Add screenshots or sample outputs for the larger exercises.
- Improve the Week 10 quiz so it supports multiple questions and scores.
- Add stronger input validation and error handling.
- Organize future projects into clearer packages as applications become larger.

---

## 🔗 Repository

**GitHub:**  
https://github.com/Adilelkhedir-hub/Adil_Elkhedir_202505010496_OOP_Java

---

## 👨‍💻 Author

**Adil Elkhedir**  
Student ID: **202505010496**  
City University Malaysia  
BIT1123 – Object-Oriented Programming


---

**Last updated:** August 2026
