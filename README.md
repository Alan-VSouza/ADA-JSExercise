# JavaScript Exercises Project

This project contains three JavaScript exercises that demonstrate various programming concepts such as list manipulation, student grade calculation, and random number generation for a lottery-like system.

## 📄 Exercises

### 1. **Exercicio1.js**
   - **Description**: This exercise separates even and odd numbers from a predefined list.
   - **Input**: A list of numbers `[1, 2, 3, 4, 5, 6, 7, 8, 9]`
   - **Output**:
     - Even numbers: `[2, 4, 6, 8]`
     - Odd numbers: `[1, 3, 5, 7, 9]`
   - **How it works**: The script uses a `for` loop to iterate through the list, dividing it into two separate arrays: one for even numbers and one for odd numbers.

### 2. **Exercicio2.js**
   - **Description**: This exercise calculates the average grade of students from a list of objects, where each object contains the student's name and two grades.
   - **Input**: A list of student objects, each containing `name` and `notas` (grades), e.g.,
     ```javascript
     [
       { nome: "João", notas: [8, 7] },
       { nome: "Maria", notas: [9, 8] }
     ]
     ```
   - **Output**: The average of all students' grades.
   - **How it works**: The script iterates over the list of students using a `for` loop, calculating the sum of each student's grades and then computing the overall average.

### 3. **Exercicio3.js**
   - **Description**: A lottery-style exercise that generates 6 random numbers between 1 and 60 without repetition.
   - **Output**: A list of 6 random, unique numbers.
   - **How it works**: The script repeatedly generates a random number between 1 and 60 using `Math.random()`. If the number is not already in the list, it is added, ensuring there are no duplicates.

## 🛠 Technologies Used
   - HTML5
   - JavaScript (ES6+)
   