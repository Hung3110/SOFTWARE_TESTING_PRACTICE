# SOFTWARE_TESTING_PRACTICE
## Student Information
- Full name: Nguyen Manh Hung
- Student ID: BIT230181
- Course: Software Testing

## Table of Contents
1. Overview
2. Repo Structure
1. Chapter 1: Testing Principles  
2. Chapter 2: Testing Process
3. Chapter 3: Cypress Exercise
4. Chapter 4: JMeter Performance Test
...

## Overview
This repository stores weekly practice work, source code, and evidence for the **Software Testing** course.

Technology Stack:
- Languages: Java (JUnit)
- Tools: VS Code, Git
- Frameworks: JUnit 5

## Repo Structure
```
SOFTWARE_TESTING_PRACTICE/
|-- cantunsee/              # Chapter 1 Exercises
|-- unit-test/              # Chapter 2 Exercises (Java Project)
|   |-- src/                # Functional Source Code
|   |-- target/
|   `-- test/               # Test Case Source Code
|-- cypress_exercise/       # Chapter 3: Cypress exercise
|-- jmeter/                 # Chapter 4: JMeter performance test
|-- evidence_images/        # Test Evidence Storage
`-- README.md               # This Documentation File
```

## Chapter 1: Testing Principles
Goal: Train observation skills ("Pixel Perfect") and distinguish UI design errors through the Can't Unsee game.
- Activities: Analyze Contrast, Typography, Alignment, and Padding.
- Result: Completed levels from basic to advanced.

Evidence:
![cantunsee_result](https://github.com/user-attachments/assets/e8dac111-d3c0-4950-9069-3c685b874ccf)

## Chapter 2: Testing Process
Goal: JUnit 5 tests for `StudentAnalyzer` (excellent count, valid average) with boundary handling.

Techniques:
- Equivalence Partitioning + Boundary Value Analysis (0, 10, empty)
- Clean Code (validate & skip invalid scores).

Evidence:
![unit-test](https://github.com/user-attachments/assets/758ebcd4-91fb-47a5-9f40-bcbc21302cf7)

## Chapter 3: Cypress Exercise
Goal: Write E2E tests for the Cypress exercise.

Stack: Cypress 13, Node 18+, npm.

How to run:
- Install deps: npm install
- Open runner: npx cypress open
- Run headless: npx cypress run

Evidence:
![cypress_result](evidence_images/chapter3/Screenshot%202026-01-22%20083846.png)
![cypress_result](evidence_images/chapter3/Screenshot%202026-01-22%20083724.png)

## Chapter 4: JMeter Performance Test
Goal: Run performance testing with JMeter on Wikipedia.
Report: `jmeter/README.MD`

Evidence:
![jmeter_summary](jmeter/evidence/Screenshot%202026-01-22%20110451.png)
![jmeter_view_results_1](jmeter/evidence/Screenshot%202026-01-22%20110528.png)
![jmeter_view_results_2](jmeter/evidence/Screenshot%202026-01-22%20110557.png)

