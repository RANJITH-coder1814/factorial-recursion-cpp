# factorial-recursion-cpp
A simple C++ program to find the factorial of a given number using recursion. The factorial of a number N is the product of all positive integers less than or equal to N.  𝑁 ! = 𝑁 × ( 𝑁 − 1 ) × ( 𝑁 − 2 ) × . . . × 1 N!=N×(N−1)×(N−2)×...×1  
# Factorial of a Number using Recursion (C++)

## 📌 Overview

This project demonstrates how to calculate the **factorial of a number using recursion** in C++.

Recursion is a technique where a function **calls itself** until a **base condition** is met.

## 🚀 Features

* Recursive implementation of factorial
* Simple and beginner-friendly
* Demonstrates base case and recursive call

## 🧠 Algorithm

1. Take input number **N**.
2. If **N is 0 or 1**, return **1** (base case).
3. Otherwise return **N × factorial(N-1)**.
4. Continue until the base case is reached.

## 💻 Code

```cpp
#include <iostream>
using namespace std;

int factorial(int n) {
    if (n == 0 || n == 1)
        return 1;

    return n * factorial(n - 1);
}

int main() {
    int n;
    cin >> n;

    cout << factorial(n);

    return 0;
}
```

## ▶️ Example

Input

```
5
```

Output

```
120
```

Explanation
5! = 5 × 4 × 3 × 2 × 1 = **120**

## ⏱️ Time Complexity

**O(N)**

## 📚 Concepts Used

* Recursion
* Base Case
* Function Calls

## 📂 Project Structure

```
factorial-recursion-cpp
│
├── main.cpp
└── README.md
```
