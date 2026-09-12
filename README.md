# Student Performance Data Processor

A Python-based data processing project that loads student performance
records from a JSON file, cleans invalid data, and generates basic
performance insights.

## Features

- Loads student data from JSON
- Removes records with missing or invalid names
- Handles missing marks
- Converts string marks to integers
- Removes marks outside the 0–100 range
- Removes duplicate student records
- Calculates average marks
- Identifies passing students
- Finds the highest-scoring student
- Generates pass/fail statistics
- Sorts students by marks
- Generates a consolidated report

## Technologies

- Python
- JSON

## Project Workflow

JSON data  
↓  
Data cleaning  
↓  
Validation  
↓  
Performance analysis  
↓  
Report generation

## What I Learned

- Working with lists and dictionaries
- Reading JSON data using `json.load()`
- Writing reusable Python functions
- Data validation and cleaning
- Handling missing and invalid values
- Type conversion
- Duplicate detection
- Sorting data using `sorted()` and `lambda`
- Building a simple data-processing pipeline
