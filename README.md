# C Programming Quiz Application

## 1. Introduction

The **C Programming Quiz Application** is a simple console-based project developed using the C programming language. It is designed to test and improve the basic knowledge of students in C programming through multiple-choice questions.

The application contains 20 questions related to C programming concepts. Each question provides four options, and the user has to select the correct answer.

At the end of the quiz, the application calculates the score and displays the user's performance.

## 2. Project Overview

| Details | Description |
|---|---|
| Project Name | C Programming Quiz Application |
| Programming Language | C |
| Project Type | Console-Based Application |
| Total Questions | 20 |
| Question Format | Multiple Choice Questions |
| Total Marks | 20 |
| Compiler | GCC |

## 3. Objectives

- To develop a basic quiz application using C.
- To test knowledge of C programming concepts.
- To understand the implementation of structures and arrays.
- To practice loops and conditional statements.
- To calculate and display the final quiz score.

## 4. Features

- Contains 20 C programming questions.
- Provides four options for each question.
- Accepts answers from the user (A, B, C, D).
- Checks answers automatically.
- Displays the correct answer for incorrect responses.
- Calculates the final score.
- Displays performance feedback based on the score.

## 5. Technologies Used

- **C Programming:** Main programming language.
- **GCC Compiler:** Used to compile and execute the program.
- **Visual Studio Code:** Used for writing and editing the source code.
- **GitHub:** Used for project storage and version control.

## 6. C Programming Concepts Used

The project demonstrates the following C programming concepts:

1. **Structures:** Used to store questions, options, and correct answers together.
2. **Arrays:** Used to store all 20 quiz questions and their options.
3. **Loops:** Used to display questions one by one.
4. **Conditional Statements:** Used to check whether the selected answer is correct.
5. **Variables:** Used to store the user's answers and total score.
6. **Functions:** Standard library functions are used for input, output, and character conversion.

## 7. Project Structure

The repository is organized as follows:

```text
C-Quiz-Application/
│
├── README.md
│
├── QuizApplication.c
│
└── Output-Screenshots/
    └── Quiz-Result.png
```

## 8. How the Application Works

1. The application starts and displays the quiz instructions.
2. The user starts the quiz.
3. The application displays one question at a time.
4. The user selects an answer from A, B, C, or D.
5. The program checks the selected answer.
6. The score increases for every correct answer.
7. After all 20 questions, the final result is displayed.

## 9. Sample Output

```text
====================================
       C PROGRAMMING QUIZ
====================================

Instructions:
1. There are 20 questions.
2. Each question carries 1 mark.
3. Enter A, B, C or D as your answer.

Question 1: Which function is used to display output in C?

A. scanf()
B. printf()
C. getch()
D. main()

Your answer: B
Correct answer!

====================================
             QUIZ RESULT
====================================

Total Questions : 20
Correct Answers : 18
Wrong Answers   : 2
Final Score     : 18/20

Performance: Excellent!

====================================
       Thank You for Playing!
====================================
```

*Note: The sample score above is only an illustration.*

## 10. How to Run the Project

**Step 1:** Download or clone the repository.

**Step 2:** Open the project folder in Visual Studio Code or another C-supported IDE.

**Step 3:** Open the terminal.

**Step 4:** Compile the program using:

```bash
gcc QuizApplication.c -o QuizApplication
```

**Step 5:** Run the application.

For Windows:

```bash
QuizApplication.exe
```

For Linux:

```bash
./QuizApplication
```

## 11. Team Members

This project was developed by the following team members:

| S. No. | Name | UID |
|---|---|---|
| 1 | Jojan | 26BCD10294 |
| 2 | Partiksha | 26BCD10292 |
| 3 | Aditi | 26BCD10277 |

## 12. Conclusion

The C Programming Quiz Application is a beginner-friendly project that demonstrates the practical use of fundamental C programming concepts.

It provides an interactive way to test programming knowledge while helping students understand how structures, arrays, loops, and conditional statements work together in a real application.

**Thank You!**
