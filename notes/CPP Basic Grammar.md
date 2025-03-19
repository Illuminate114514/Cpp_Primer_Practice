# CPP Basic Grammar 

## Structure of a C++ Program

A C++ program typically consists of:
- Preprocessor directives (#include <iostream>)
- Main function (int main() {})
- Statements and expressions (std::cout << "Hello, World!";)

Example:
#include <iostream>  // Preprocessor directive

int main() {  // Main function
    std::cout << "Hello, World!" << std::endl;  // Output statement
    return 0;  // Return statement
}

## Variables and Data Types

Basic Data Types:
- int (Integer)
- double (Floating-point)
- char (Character)
- bool (Boolean)
- void (No value, used in functions)

int age = 25;
double pi = 3.14159;
char grade = 'A';
bool isPass = true;

## Operators
### Operators in C++

| **Type**       | **Operators**                  | **Example** |
|---------------|--------------------------------|-------------|
| Arithmetic   | `+`, `-`, `*`, `/`, `%`        | `a + b`     |
| Relational   | `==`, `!=`, `<`, `>`, `<=`, `>=` | `a > b`     |
| Logical      | `&&`, `||`, `!`                | `a && b`    |
| Bitwise      | `&`, `|`, `^`, `~`, `<<`, `>>`  | `a & b`     |
| Assignment   | `=`, `+=`, `-=`, `*=`, `/=`, `%=` | `a += 1`   |

## Control Flow Statements
### Conditional Statements
**if-else Statement**
int x = 10;
if (x > 5) {
    std::cout << "x is greater than 5";
} else {
    std::cout << "x is 5 or less";
}

**switch-case Statement**
int choice = 2;
switch (choice) {
    case 1: std::cout << "Option 1"; break;
    case 2: std::cout << "Option 2"; break;
    default: std::cout << "Invalid choice";
}

### Looping Statements
**for Loop**
for (int i = 0; i < 5; i++) {
    std::cout << i << " ";
}

**while Loop**
int i = 0;
while (i < 5) {
    std::cout << i << " ";
    i++;
}

**do-while Loop**
int i = 0;
do {
    std::cout << i << " ";
    i++;
} while (i < 5);

## Functions













