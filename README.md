# Characters A to Z - Java Program

## 📌 Description

This Java program prints all the uppercase alphabets from **A to Z** using a simple `for` loop. It is a great beginner-level program to understand how **character data types**, **loops**, and **ASCII values** work in Java.

---

## 🧾 Source Code

```java
package question_bank.Number_Programs;

public class Characters_A_to_Z 
{
    public static void main(String[] args) 
    {
        for(char ch = 'A'; ch <= 'Z'; ch++) 
        {
            System.out.print(ch + " ");
        }
    }
}
```

---

## 🔍 Explanation

### 1. Package Declaration

```java
package question_bank.Number_Programs;
```
- This line declares the package in which the class resides. It helps organize the files and avoid class name conflicts in large projects.

### 2. Class Declaration

```java
public class Characters_A_to_Z
```
- A public class named `Characters_A_to_Z` is defined. The class name is in PascalCase, which is a standard naming convention in Java.

### 3. Main Method

```java
public static void main(String[] args)
```
- The `main` method is the entry point of any Java application. 
- It is `public` so that it can be accessed from outside the class.
- It is `static` so that the JVM can call it without creating an instance of the class.
- `String[] args` is used to accept command-line arguments.

### 4. For Loop

```java
for(char ch = 'A'; ch <= 'Z'; ch++)
```
- A `for` loop is used to iterate from the character `'A'` to `'Z'`.
- Characters in Java can be incremented because they are based on **ASCII values**.
- `'A'` has an ASCII value of 65 and `'Z'` has 90.

### 5. Print Statement

```java
System.out.print(ch + " ");
```
- This prints each character followed by a space.
- `print()` is used instead of `println()` to keep output on the same line.

---

## 🧾 Output

```
A B C D E F G H I J K L M N O P Q R S T U V W X Y Z 
```

---

## 📘 Concepts Covered

- Java Data Types (char)
- Loops (`for` loop)
- ASCII values
- Printing to console
- Java package organization

---

## Clone
```
git clone https://github.com/Ananthadatta02/Java-Characters_A_to_Z.git
```
