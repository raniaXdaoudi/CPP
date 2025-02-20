# CPP Modules

A series of C++ modules designed to learn Object-Oriented Programming. This project is part of the 42 school curriculum.

## Description

This project consists of multiple modules, each focusing on specific aspects of C++ and Object-Oriented Programming. The modules progress from basic C++ concepts to more advanced features, helping to understand the transition from C to C++ and the principles of OOP.

## Modules Overview

### CPP Module 00
- Namespaces
- Classes
- Member functions
- stdio streams
- Initialization lists
- Static
- Const
- Basic stuff

### CPP Module 01
- Memory allocation
- Pointers to members
- References
- Switch statement

### CPP Module 02
- Ad-hoc polymorphism
- Operator overloading
- Orthodox Canonical class form

### CPP Module 03
- Inheritance
- Virtual functions
- Access specifiers

### CPP Module 04
- Subtype polymorphism
- Abstract classes
- Interfaces

### CPP Module 05
- Repetition and Exceptions
- Error handling
- Try-catch blocks

### CPP Module 06
- C++ casts
- Type conversion
- Type reinterpretation

### CPP Module 07
- C++ templates
- Template specialization
- Default type parameters

### CPP Module 08
- Templated containers
- Iterators
- Algorithms

### CPP Module 09
- STL Containers
- Built-in algorithms
- Real-world applications

## Getting Started

### Prerequisites
- C++ compiler (g++ recommended)
- Make
- Unix-based operating system (Linux/Mac)

### Installation
```bash
git clone https://github.com/yourusername/CPP.git
cd CPP/CPPxx # where xx is the module number
make
```

### Usage
Each module contains multiple exercises, each with its own executable. To run a specific exercise:
```bash
cd CPPxx/exYY # where xx is the module number and YY is the exercise number
make
./executable_name
```

## Implementation Details

Each module focuses on specific C++ concepts and includes:
1. Multiple exercises demonstrating different aspects
2. Proper memory management
3. Orthodox Canonical class form when required
4. Operator overloading where appropriate
5. Proper exception handling
6. Template usage in later modules

## Error Handling
The programs handle various error cases:
- Invalid input
- Memory allocation failures
- File operations errors
- Custom exceptions
- Type conversion errors

## Building
Each exercise includes a Makefile with the following rules:
- `make` - Compiles the program
- `make clean` - Removes object files
- `make fclean` - Removes object files and executable
- `make re` - Rebuilds the program

## Coding Standards
All code follows:
- Orthodox Canonical class form when required
- Proper naming conventions
- Clear and maintainable structure
- Efficient memory management
- C++98 standard compliance

## Author
- Rania (radaoudi)

## License
This project is part of the 42 school curriculum. Please refer to 42's policies regarding code usage and distribution.

## Acknowledgments
- 42 school for providing the project requirements and framework
- C++ standard documentation and references
