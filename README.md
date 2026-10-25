
# MATLAB and Python for Neuroscience

## Overview

This repository contains practical programming exercises completed during a six-session educational training program focused on programming for neuroscience using MATLAB and Python.

The training covered programming fundamentals, EEG data representation, signal visualization, data structures, functions, control flow, and basic signal quality assessment. The exercises progressed from introductory programming concepts to integrated EEG data analysis tasks.

## Session 1 — MATLAB Fundamentals and Data Preparation

**Topics:** Variables, data types, matrices, vectors, indexing, and operators.

- Created numeric, string, and logical variables.
- Explored matrix dimensions and data types using `size()`, `class()`, and `whos`.
- Generated row and column vectors, zero matrices, identity matrices, and random data using `randn()`.

## Session 2 — EEG Visualization and Logical Operations

**Topics:** Statistical plots, signal simulation, logical operators, and outlier detection.

- Simulated brain activity across three conditions and compared group means using bar charts.
- Visualized data distributions and interquartile ranges using boxplots.
- Displayed frequency-band power with pie charts and amplitude distributions with histograms.
- Applied logical operators (`>`, `&`, `|`, and `xor`) to identify samples meeting specific conditions.
- Simulated noisy EEG signals, detected potential outliers using standard deviation thresholds, and visualized them with scatter plots.

## Session 3 — MATLAB Functions and Control Flow

**Topics:** Functions, loops, conditional statements, and control-flow commands.

- Developed functions to replace negative values with zero and sum positive numbers.
- Used `break` to identify the first value exceeding a threshold.
- Applied `continue` to skip unwanted values.
- Evaluated student grades using loops, conditions, and input validation.

## Session 4 — Python Fundamentals and String Manipulation

**Topics:** Variables, strings, built-in methods, user input, and formatted output.

- Created EEG channel labels and counted character occurrences.
- Converted strings to uppercase and lowercase.
- Collected user input and processed text using string methods.
- Represented EEG recording characteristics using variables and formatted tables.

## Session 5 — Python Data Structures and Text Processing

**Topics:** Dictionaries, sets, lists, and string processing.

- Organized EEG frequency-band information using dictionaries and sets.
- Updated values and identified minimum and maximum power values.
- Replaced spaces, split EEG reports into individual terms, and extracted unique words.
- Practiced basic data organization and text processing.

## Session 6 — Python Functions and EEG Signal Quality Assessment

**Topics:** Functions, lambda expressions, sorting, filtering, and control flow.

- Developed functions to validate EEG amplitudes against specified thresholds.
- Used lambda expressions to perform arithmetic operations on signal values.
- Sorted and filtered channels according to amplitude criteria.
- Removed noise values and assessed average signal activity.
- Built an integrated `analyze_session()` function to count potential artifacts, calculate average valid amplitudes, and generate summary reports for multiple subjects.

## Tools and Technologies

- MATLAB
- Python

## Key Skills

Programming Fundamentals, EEG Data Representation, Signal Visualization, Statistical Plotting, Data Structures, Function Development, Control Flow, Logical Operations, Data Filtering, and Basic Artifact Detection.

## Training Mentors

- Negar Sobhi
- Ensieh Shafigh

## Project Type

Educational / Practical Training

## Status

Completed

## Note

This repository documents completed educational exercises using simulated data and simplified EEG analysis rules. The examples are intended for learning purposes and do not constitute a clinically validated EEG analysis pipeline.
