Awesome! Here's a **comprehensive GitHub Classroom-style assignment** covering all the following topics:

- ✅ What is a Method  
- ✅ Naming and Best Practices  
- ✅ Declaring and Invoking Methods  
- ✅ Void and Return Type Methods  
- ✅ Methods with Parameters  
- ✅ Value vs. Reference Types  
- ✅ Overloading Methods  

---

# 📘 **Java Methods & Fundamentals – Assignment**

## 🎯 Objective

The goal of this assignment is to strengthen your understanding of **Java methods**. You will apply best practices in method naming, understand how data is passed (by value or reference), and implement overloaded methods to simulate real-world behavior.

---

## 📂 Project Structure

```
java-methods-assignment/
├── src/
│   ├── StudentManager.java
│   ├── Calculator.java
│   ├── Logger.java
│   ├── Demo.java
├── README.md
└── .gitignore
```

---

## 🧑‍🏫 Assignment Tasks

### ✅ 1. `StudentManager.java`
Create a class that demonstrates:
- A method to **print student details** (name, age, GPA).
- A method to **calculate GPA** (takes 3 scores and returns average).
- Apply **method naming best practices**.
- Use **parameters** and **return values** effectively.

📌 Example usage:
```java
printStudentInfo("Alice", 20, 3.7);
double gpa = calculateGPA(88, 92, 79);
```

---

### ✅ 2. `Calculator.java`
Create a calculator with **overloaded `add()` methods** that support:
- `int add(int, int)`
- `double add(double, double)`
- `int add(int, int, int)`

Also include:
- `multiply(int, int)`
- `multiply(double, double)`

📌 Output should demonstrate the difference.

---

### ✅ 3. `Logger.java`
- Build a utility logger class with:
  - `log(String message)`
  - `log(String level, String message)`
  - `log(String message, boolean timestamped)`

- Bonus: Use `LocalTime` to prepend timestamps if needed.
- Reinforces **method overloading** and **optional behavior**.

---

### ✅ 4. `Demo.java`
Create a `main()` class that:
- Demonstrates all classes and methods.
- Showcases the difference between **value and reference** types:
  - Pass a primitive into a method that attempts to change it.
  - Pass an array and change it inside a method.

📌 Sample:
```java
int x = 10;
modifyValue(x); // should not change x

int[] numbers = {1, 2, 3};
modifyArray(numbers); // should change first element
```

---

## 📜 Requirements

- Follow **Java naming conventions**.
- Write **JavaDocs-style comments** above each method.
- Organize your code in a `src/` folder.
- Use only **Java 8+** features.

---

## 🧪 Sample Output

```
== Student Manager ==
Student: Alice, Age: 20, GPA: 3.7

== Calculator ==
add(2, 3): 5
add(2.5, 3.5): 6.0
add(1, 2, 3): 6

== Logger ==
Message: Welcome!
[INFO] App started
[10:40:21] Running scheduled task

== Value vs Reference ==
Primitive value: 10
After method: 10
Array first value before: 1
Array first value after: 999
```

---

## 📚 References

- [Java Methods (Oracle)](https://docs.oracle.com/javase/tutorial/java/javaOO/methods.html)
- [Method Overloading in Java – GeeksForGeeks](https://www.geeksforgeeks.org/method-overloading-in-java/)
- [Value vs Reference (Baeldung)](https://www.baeldung.com/java-value-vs-reference)
- [Java Naming Conventions (Oracle)](https://www.oracle.com/java/technologies/javase/codeconventions-namingconventions.html)

---

## 🧠 Bonus (Optional)
Add unit tests using **JUnit 5** to test:
- Calculator methods
- Logger output (just dummy assertions)
- Student GPA calculations

---

## 📥 Submission Instructions (GitHub Classroom)

1. Clone the GitHub Classroom repository.
2. Complete the code inside the `src/` directory.
3. Commit and push your changes.


---

## 🏁 Grading Rubric

| Criteria                       | Points |
|-------------------------------|--------|
| Method Naming and Structure   | 20     |
| Void vs Return Usage          | 10     |
| Parameter Handling            | 15     |
| Overloading Usage             | 15     |
| Value vs Reference Demo       | 10     |
| Working Main Demo             | 10     |
| Clean Code & Comments         | 10     |
| Bonus: Unit Tests             | +10    |

---
