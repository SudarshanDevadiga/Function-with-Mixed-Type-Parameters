# Function with Mixed Type Parameters

A simple C++ program demonstrating a function that takes parameters of different data types (int and float).

## Description

This program defines a function `displayNum` that accepts an integer and a floating-point number as arguments and displays them on the console. It showcases the ability of C++ functions to handle different data types.

### Key Features
- Function with mixed type parameters
- Simple output formatting
- Demonstrates data type handling

## Code Structure

```cpp
#include<iostream>
using namespace std;

void displayNum(int n1, float n2) {
    cout << "The int number is " << n1 << endl;
    cout << "The double number is " << n2;
}

int main() {
    int num1 = 5;
    double num2 = 5.5;
    displayNum(num1, num2);
    return 0;
}
