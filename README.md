 # C++ Data Analyzer

C++ project that generates, reads, and analyzes numeric datasets using object-oriented design.
The program performs duplicate detection, missing-value analysis, descriptive statistics, and random search testing on a generated data file.

# Overview

Project was originally developed as a C++ coursework assignment and later polished for portfolio use.
Its purpose is to demonstrate core programming concepts:

- file input/output
- dynamic memory management
- inheritance and polymorphism 
- sorting and binary search 
- basic statistical analysis 
- modular program structure

# Features

Generates a dataset of random integers 
Writes the dataset to a file Reads values back into memory 
Detects duplicate values Identifies missing numbers in the expected range 
Computes: 
 - minimum 
 - maximum 
 - mean 
 - median 
 - mode 

Performs randomized search trials using binary search

# Project Structure

main.cpp is the main driver and program logic 
README.md is the project description and usage instructions 
numbers.txt is the generated input data file

# Concepts

This project highlights several foundational C++ concepts like

- classes and abstract base classes 
- derived analyzer classes 
- constructors and destructors 
- recursive binary search 
- bubble sort 
- file parsing with streams 
- array based data processing

# How Does it Work?

A dataset of random integers is generated.
The values are written to a file.
The file is read back into an array.
Multiple analyzer classes process the dataset independently: 
- duplicate analyzer 
- missing-value analyzer 
- statistics analyzer 
- search analyzer
Results are printed to the console.
