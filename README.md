# Overview

RPAL(Right-reference Pedagogic Algorithmic Language) is a simple functional programming 
language which is a subset of PAL, that was developed by MIT.

This is an academic project done as part of the Semester 4 Programming Languages Module. For 
this project a Lexical Analyzer, Parser, Abstract Syntax Tree Generator, Standardizer, and 
Control Stack Evaluation(CSE) Machine were built using Python. This allows the user to run 
programs and algorithms in the RPAL Language. Given below is a high level structure of the 
Interpreter. <br><br>
![image](https://github.com/user-attachments/assets/11073862-f2b2-4e78-9dca-62394246718b)

## How to Use Interpreter
Building AST 
```
python myrpal.py example.rpal -ast

```

Build Standardized Tree 
```
python myrpal.py example.rpal -ast

```

Build Control Structures 
```
python myrpal.py example.rpal -cs

```

Build CSE machine 
```
python myrpal.py example.rpal -cse

```

Print Solution 
```
python myrpal.py example.rpal

```
