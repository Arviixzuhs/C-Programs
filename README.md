# 📚 C-Programs

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/Arviixzuhs/C-Programs?style=for-the-badge)](https://github.com/Arviixzuhs/C-Programs/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Arviixzuhs/C-Programs?style=for-the-badge)](https://github.com/Arviixzuhs/C-Programs/network)
[![GitHub issues](https://img.shields.io/github/issues/Arviixzuhs/C-Programs?style=for-the-badge)](https://github.com/Arviixzuhs/C-Programs/issues)
[![Language](https://img.shields.io/badge/Language-C-blue?style=for-the-badge)](https://en.wikipedia.org/wiki/C_(programming_language))

**A curated collection of C programs designed to teach core concepts through practical, runnable examples.**

</div>

---

## 📚 Table of Contents

- [About The Project](#-about-the-project)
- [Learning Scope](#-learning-scope)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
  - [Prerequisites](#-prerequisites)
  - [Compilation & Execution](#-compilation--execution)
- [Project Structure](#-project-structure)
- [Design Philosophy](#-design-philosophy)
- [Contributing](#-contributing)
- [Author](#-author)

---

## 🚀 About The Project

**C-Programs** is an educational repository focused on learning the C programming language through hands-on practice.

This project provides:

- Clear and minimal C examples
- Fundamental programming concepts
- Practical algorithm implementations
- Structured organization by topic
- Ready-to-compile standalone programs

The goal is to reinforce theoretical knowledge with executable code that can be compiled, modified, and experimented with directly.

---

## 📖 Learning Scope

The repository covers core areas of C programming:

- 🖨 Basic Input / Output (`printf`, `scanf`)
- 🔁 Control Flow (`if`, `switch`, loops)
- 🧩 Functions and modular code
- 📦 Arrays and multi-dimensional arrays
- 📍 Pointers and pointer arithmetic
- 🔤 Strings and character manipulation
- 🏗 Structures and unions
- 📂 File handling (read/write)
- 💾 Dynamic memory allocation (`malloc`, `calloc`, `realloc`, `free`)
- 🧠 Basic algorithms (sorting, searching, recursion)
- 🖥 Command-line arguments

The collection is continuously expandable as new examples are added.

---

## 🛠 Tech Stack

### Language
- C (ANSI C)

### Compiler Options
- GCC (recommended)
- Clang
- Any standard-compliant C compiler

---

## ⚙️ Getting Started

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Arviixzuhs/C-Programs.git
cd C-Programs
```

---

## 🧰 Prerequisites

You need a C compiler installed.

### Linux (Debian/Ubuntu)

```bash
sudo apt update
sudo apt install build-essential
```

### macOS

```bash
xcode-select --install
```

### Windows

- Install **MinGW-w64**
- Or use **WSL** and follow Linux instructions

---

## ▶ Compilation & Execution

Each `.c` file is standalone.

### Compile

```bash
gcc -o program_name program_name.c
```

### Run

```bash
./program_name
```

---

### Example

```c
#include <stdio.h>

int main() {
    printf("Hello, C Programs!\n");
    return 0;
}
```

Compile & Run:

```bash
gcc -o hello hello.c
./hello
```

Output:

```
Hello, C Programs!
```

---

## 📁 Project Structure

```
C-Programs/
│
├── About/               # Notes and additional resources
│
└── Examples/
    ├── BasicIO/
    ├── ControlFlow/
    ├── Functions/
    ├── Arrays/
    ├── Pointers/
    ├── Strings/
    ├── Structures/
    ├── FileHandling/
    └── Algorithms/
```

Each folder groups examples by concept for progressive learning.

---

## 🎯 Design Philosophy

- Minimal and focused examples
- One concept per program when possible
- Clear and readable formatting
- Educational-first structure
- No unnecessary abstractions
- Emphasis on understanding memory and low-level behavior

---

## 🤝 Contributing

1. Fork the repository  
2. Create a feature branch  
3. Add a well-documented C example  
4. Follow clean coding practices  
5. Open a Pull Request  

Please keep examples simple, readable, and concept-focused.

---

## 👨‍💻 Author

Developed by **Arviixzuhs**

If you find this repository helpful for learning C, consider leaving a ⭐.
