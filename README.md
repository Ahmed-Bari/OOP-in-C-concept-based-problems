# OOP-in-C++-concept-based-problems
# Simple Graph and Attributed Graph

This project implements a simple graph data structure and an attributed graph in C++. The simple graph is a basic representation of nodes and edges, while the attributed graph extends the simple graph by adding attributes to the nodes.

## Table of Contents

- [Introduction](#introduction)
- [How to Use](#how-to-use)
- [File Structure](#file-structure)
- [Author](#author)
- [License](#license)

## Introduction

This project consists of two main classes:
- `SimpleGraph`: Implements a basic graph structure with nodes and edges.
- `AttributedGraph1`: Extends `SimpleGraph` and adds attributes (age and gender) to the nodes.

The program allows you to create nodes, add edges between nodes, and append attributes to nodes in the attributed graph.

## How to Use

1. Clone this repository to your local machine.
2. Compile the code using your C++ compiler. You can compile individual files, such as `main.cpp`, `SimpleGraph.cpp`, and `AttributedGraph1.cpp`, and link them together.
3. Run the compiled program.

The program will prompt you to enter node IDs, create nodes, add edges, and append attributes to nodes in the attributed graph.

## File Structure

- `main.cpp`: The main program that demonstrates how to create and use `SimpleGraph` and `AttributedGraph1`.
- `SimpleGraph.h` and `SimpleGraph.cpp`: Define and implement the `SimpleGraph` class, which represents the basic graph structure.
- `SimpleNode.h` and `SimpleNode.cpp`: Define and implement the `SimpleNode` class, which represents nodes in the simple graph.
- `AttributedGraph1.h` and `AttributedGraph1.cpp`: Define and implement the `AttributedGraph1` class, which extends `SimpleGraph` by adding attributes to nodes.
- `AttributedNode1.h` and `AttributedNode1.cpp`: Define and implement the `AttributedNode1` class, which represents nodes with age and gender attributes.
- `AttributedNode2.h` and `AttributedNode2.cpp`: Define and implement the `AttributedNode2` class (not used in this code example but provided for extensibility), which represents nodes with additional attributes.

## Author

Ahmed Bari

## License

This project is open-source and available under the [MIT License](LICENSE).
