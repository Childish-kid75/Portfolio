# Buffer Overflow Demonstration (EHA361 - Milestone 2)

## 📋 Overview
Demonstration of buffer overflow vulnerability in C programming, showing how memory corruption can lead to security breaches.

## 🎯 What Was Demonstrated
- Buffer overflow in C program
- Segmentation fault crash
- Memory corruption understanding
- Security implications

## 🛠️ Technologies Used
- C Programming
- GCC Compiler
- Kali Linux VM

## 🔧 Key Code
```c
#include <stdio.h>
#include <string.h>

int main() {
    char buffer[10];
    strcpy(buffer, "This is too long for buffer!");
    return 0;
}
