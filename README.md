# Advanced Python Programming Projects

This repository contains my implementations of various Python programming projects focusing on advanced Python techniques and concepts. Each project demonstrates different aspects of Python's capabilities, from object-oriented programming to functional programming paradigms.

## Stack of Technologies and Techniques

- **Python 3.9+**
- **Object-Oriented Programming (OOP)**
- **Functional Programming**
- **Iterator Protocol**
- **Generator Functions**
- **Context Managers**
- **Lazy Evaluation**
- **Named Tuples**
- **CSV Processing**
- **Data Validation**
- **Dictionary Manipulation**
- **ChainMaps**
- **JSON Serialization/Deserialization**
- **Custom Encoders/Decoders**
- **Marshmallow Schema**
- **Datetime and Decimal Handling**

## Projects Overview

### 1. Polygon Sequence

Implementation of a sequence type that returns a series of regular convex Polygon objects with various properties including:
- Number of vertices/edges
- Edge length
- Apothem
- Surface area
- Perimeter
- Interior angle

Features:
- Immutable polygon objects
- Support for equality and ordering
- Full slicing and indexing capabilities
- Calculation of polygon with highest area:perimeter ratio

### 2. Lazy Properties Polygon Sequence

Refactored version of the Polygon project with:
- Lazy property evaluation for calculated properties
- Implementation of both iterable and iterator protocols
- Lazy computation of polygon elements

### 3. NYC Parking Tickets Analysis

Processing and analysis of NYC parking ticket data:
- Lazy iterator returning named tuples with appropriate data types
- Analysis of violations by car make
- Efficient data processing techniques

### 4. Multi-File Person Data Processing

Processes personal information from multiple CSV files:
- Creates iterators for cleaning data from 4 different files
- Combines columns from all iterators into a single iterable
- Filters stale records based on update dates
- Finds largest groups of car makes by gender

### 5. CSV Context Manager

Implementation of:
- A class-based context manager for reading CSV files into named tuples
- A generator-based context manager using contextlib
- Lazy iterators for data processing

### 6. Dictionary Validation

JSON structure validation against templates:
- Recursive validation of nested dictionary structures
- Type checking for dictionary values
- Comprehensive error reporting


### 7. JSON Serialization and Deserialization

Custom serialization and deserialization of complex Python objects:
- Implementation of custom JSONEncoder for Stock and Trade classes
- Support for non-standard Python types (Decimal, datetime, date)
- Type preservation during serialization/deserialization cycle
- Alternative implementation using Marshmallow schema
- Handling of nested object structures in dictionaries


### 8. Dictionary Manipulation Exercises

Multiple techniques for dictionary operations:
- Merging dictionaries from multiple sources using defaultdict and Counter
- Creating dictionaries with predefined keys
- Merging configuration files using ChainMap

## Getting Started

```
# Clone the repository
git clone https://github.com/yourusername/advanced-python-projects.git

# Navigate to project directory
cd advanced-python-projects

# Run tests
python -m unittest discover
```

## Key Implementation Details

- **Lazy Evaluation**: Minimizing computation by calculating values only when needed
- **Memory Efficiency**: Using iterators and generators to process large datasets without loading everything into memory
- **Composition**: Building complex functionality through composition of simpler components
- **Functional Approach**: Using map, filter, and other functional programming techniques
- **Clean Object-Oriented Design**: Proper encapsulation and implementation of Python's special methods
- **Serialization Strategies**: Multiple approaches to object serialization preserving type information
- **Schema Validation**: Enforcing data structures through schema definition and validation