# Homework #15: Java Concurrency and Multithreading

## Introduction
In this homework assignment, you will apply your knowledge of Java concurrency and multithreading. The tasks are designed to simulate real-world scenarios where concurrency plays a critical role.

## Tasks
You have three tasks to complete, each focusing on different aspects of concurrency and multithreading in Java.

### Task 1: Web Server Request Simulator
- **Objective**: Simulate a web server processing multiple incoming requests concurrently using an Executor Service.
- **Requirements**:
    - Simulate incoming requests as tasks.
    - Use an Executor Service with a fixed thread pool.
    - Implement a mechanism to simulate varying arrival rates of requests.

### Task 2: Future Stock Price Predictor
- **Objective**: Use Callable and Future to simulate fetching future stock prices.
- **Requirements**:
    - Implement Callable tasks that predict stock prices (randomly generated for simplicity).
    - Use an ExecutorService to submit Callable tasks for different stocks.
    - Retrieve and display the predicted prices using Future objects.

### Task 3: Semaphore-Controlled Database Access
- **Objective**: Simulate multiple users accessing a database concurrently, controlled by a Semaphore.
- **Requirements**:
    - Use a Semaphore to limit the number of concurrent accesses.
    - Simulate users trying to access a shared resource (database).
    - Print messages indicating when users are accessing or leaving the database.

## Submission
Submit your completed assignments by 2023-11-16. Ensure your code is well-commented, demonstrating your understanding of the concepts.

Good luck!
