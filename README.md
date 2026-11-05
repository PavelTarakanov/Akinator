# Akinator Tree Project

A classic **Akinator game** implementation in C++ built around a binary tree data structure. The program guesses objects (or concepts), learns new entries dynamically, and provides definitions and comparisons between items.

## Features
- **Interactive Akinator Gameplay:** Play against the knowledge tree, answer "Yes/No", and teach the computer new objects if it fails.
- **Tree Persistence:** Load and save the knowledge base from/to structured text files[cite: 8].
- **Definitions & Comparisons:** Find definitions for specific terms or compare similarities and differences between two objects[cite: 6].
- **Graph Visualization:** Automatically generates visual Graphviz (`.dot` to `.png`) dumps of the binary tree structure[cite: 6, 8].

## Project Structure
- `tree.cpp` / `tree.h` — Core binary tree logic, file parsing, and Akinator gameplay loop.
- `file_using.cpp` / `file_using.h` — Safe file opening/closing wrappers[cite: 3, 4].
- `tree.txt` — Default database of nodes and questions[cite: 8].

## Getting Started

Compile project and start working.

'''bash
./list.out <file_with_tree>
'''


