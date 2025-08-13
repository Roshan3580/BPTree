# BPTree

BPTree is an implementation of a B+Tree data structure designed to efficiently store, retrieve, and manage large sets of sorted data. The B+Tree is widely used in database and file systems due to its ability to handle dynamic insertions, deletions, and range queries with logarithmic time complexity.
![](./docs/chart.gif)
This project provides the following features:

- Insertion of key-record pairs into the B+Tree
- Deletion of keys from the B+Tree
- Efficient range queries to retrieve all records within a specified key range
- Exporting the current state of the B+Tree for grading or visualization
- Generation of a visual chart of the B+Tree structure

The B+Tree operates over keys stored in an unordered heap, ensuring that all operations remain efficient even as the dataset grows. This makes it suitable for educational purposes, database indexing, and systems that require fast and reliable data access.

