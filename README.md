# RPAL Interpreter

This repository contains an implementation of an interpreter for RPAL (Right-reference Pedagogic Algorithmic Language), a functional programming language developed as a subset of PAL by MIT. The interpreter is built using Python and is designed to allow users to run programs and algorithms written in the RPAL language.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [How to Use the Interpreter](#how-to-use-the-interpreter)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Prerequisites](#prerequisites)


## Project Overview
This project was developed as part of the Semester 4 Programming Languages Module. The interpreter is capable of reading an input file containing an RPAL program, tokenizing the program, building a parse tree, generating an Abstract Syntax Tree (AST), standardizing the AST, and finally evaluating the program using a Control Stack Evaluation (CSE) Machine. The project is structured into various components, each of which has been implemented in Python.

![Project Flow](https://github.com/user-attachments/assets/11073862-f2b2-4e78-9dca-62394246718b)

### Key Components:
- **Lexical Analyzer**: Converts the RPAL code into tokens.
- **Parser**: Builds a parse tree from the token list.
- **AST Generator**: Converts the parse tree into an Abstract Syntax Tree (AST).
- **Standardizer**: Standardizes the AST as per RPAL rules.
- **CSE Machine**: Evaluates the standardized AST to produce the final output.

## Features
- **Tokenization**: Efficient lexical analysis of RPAL code.
- **Syntax Analysis**: Parser with robust error handling for syntax issues.
- **AST Generation**: Generates and outputs an Abstract Syntax Tree.
- **Standardization**: Transforms the AST into a standardized format.
- **CSE Machine**: Flattens and evaluates the standardized AST.

## Project Structure
The project is organized into several Python scripts, each handling a specific aspect of the RPAL interpreter:

- `Scanner.py`: Lexical analysis and tokenization.
- `Parser1.py`: Syntax analysis and parse tree generation.
- `AST.py`: AST generation and printing.
- `ST.py`: Standardization of the AST.
- `ControlStructure.py`: Generation of control structures for the CSE machine.
- `CSEM.py`: Evaluation of control structures using the CSE machine.
- `myrpal.py`: Main script to execute the interpreter.

## How to Use the Interpreter
To use the RPAL interpreter, replace `example.rpal` with your RPAL code file in the following commands.

### Build AST
```bash
python myrpal.py example.rpal -ast
```

### Build Standardized Tree
```bash
python myrpal.py example.rpal -st
```

### Build Control Structures
```bash
python myrpal.py example.rpal -cs
```

### Run CSE Machine
```bash
python myrpal.py example.rpal -cse
```

### Print Solution
```bash
python myrpal.py example.rpal
```

## Getting Started

This section provides a guide to setting up the RPAL interpreter on your local machine.

### Prerequisites

Before running the interpreter, ensure you have the following installed on your machine:
- Python 3.6 or higher
- A text editor or an Integrated Development Environment (IDE) like Visual Studio Code or PyCharm

### Installation

1. **Clone the Repository**: 

```bash
git clone https://github.com/k-ranasinghe/rpal-interpreter.git
```

2. **Navigate to the Project Directory**: 

```bash
cd rpal-interpreter
```

3. **Run the Interpreter**: Execute the myrpal.py script as per the instructions in the [How to Use the Interpreter](#how-to-use-the-interpreter) section.



