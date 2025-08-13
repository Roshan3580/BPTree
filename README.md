# BPTree

BPTree is a practical implementation of the B+Tree data structure, crafted to efficiently store, retrieve, and manage large collections of sorted data. This structure is a favorite in database and file systems because it can handle dynamic insertions, deletions, and range queries with impressive logarithmic time complexity.

![](./docs/chart.gif)

This project provides the following features:

- Insert key-record pairs into the B+Tree
- Delete keys from the B+Tree
- Perform efficient range queries to fetch all records within a specific key range
- Export the current state of the B+Tree for grading or visualization
- Generate a visual chart of the B+Tree structure

The B+Tree works with keys stored in an unordered heap, which keeps all operations efficient, even as the dataset expands. This makes it perfect for educational purposes, database indexing, and systems that need quick and reliable data access.
