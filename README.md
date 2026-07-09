# # README

## Title

**University Management System Using Inheritance in Python**

## Project Description

This project demonstrates the concept of **Object-Oriented Programming (OOP)** in Python by modeling a simple university management system. It uses inheritance to create specialized classes (`Student` and `Lecturer`) from a common parent class (`Person`).

The program shows how code can be reused through inheritance while allowing child classes to have their own unique attributes and methods.

---

## Objectives

* Demonstrate the use of classes and objects in Python.
* Show how inheritance promotes code reusability.
* Illustrate method overriding using a child class.
* Demonstrate the use of the `super()` function.
* Simulate basic university operations such as student enrollment and lecturer course assignment.

---

## Classes

### 1. Person (Parent Class)

The `Person` class serves as the base class for all people in the system.

**Attributes**

* `name` – Stores the person's name.
* `age` – Stores the person's age.

**Method**

* `display_info()` – Displays the person's name and age.

---

### 2. Student (Child Class)

The `Student` class inherits from the `Person` class.

**Additional Attribute**

* `student_id` – Stores the student's identification number.

**Methods**

* `enroll_course(course)` – Displays the course the student has enrolled in.
* `display_info()` – Overrides the parent method to display the student's ID along with the inherited information.

---

### 3. Lecturer (Child Class)

The `Lecturer` class also inherits from the `Person` class.

**Additional Attribute**

* `employee_id` – Stores the lecturer's employee ID.

**Method**

* `teach_course(course)` – Displays the course the lecturer is teaching.

---

## OOP Concepts Used

### Classes and Objects

The program defines three classes and creates objects from them.

### Inheritance

Both `Student` and `Lecturer` inherit common attributes and methods from the `Person` class.

### Method Overriding

The `Student` class overrides the `display_info()` method to include the student ID.

### Encapsulation

Each object stores its own data using instance attributes.

### Code Reusability

The parent class eliminates duplication by providing common functionality that child classes inherit.

---

## Program Workflow

1. Create a `Student` object.
2. Create a `Lecturer` object.
3. Display the student's information.
4. Enroll the student in a course.
5. Display the lecturer's information.
6. Assign the lecturer to teach a course.

---

## Sample Output

```
Student Information:
Name: Gabriel
Age: 21
Student ID: ST12345
Gabriel has enrolled in Object-Oriented Programming.

Lecturer Information:
Name: Dr. Mensah
Age: 45
Dr. Mensah is teaching Object-Oriented Programming.
```

---

## Requirements

* Python 3.x

---

## How to Run

1. Save the code as `university_management.py`.
2. Open a terminal or command prompt.
3. Navigate to the folder containing the file.
4. Run the following command:

```bash
python university_management.py
```

---

## Conclusion

This project provides a simple but effective demonstration of Object-Oriented Programming principles in Python. It highlights the use of inheritance, method overriding, object creation, and code reuse to build a basic university management system. The project can be expanded further by adding more classes, attributes, and functionalities such as course registration, grading, and staff management.
