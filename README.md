# Algorithms and Data Structures

Python implementations and coursework for **1DL210 — Algorithms and Data Structures I** at Uppsala University.

This repository collects four Jupyter notebook assignments covering sorting, hash tables, and binary search trees. The notebooks contain algorithm implementations, exercises, and, where applicable, experiments or automated checks.

## Assignments

| Assignment | Topic | Contents | Notebook |
| --- | --- | --- | --- |
| 1 | Sorting basics | Insertion sort, selection sort, sink sort, runtime comparisons and approximations | [1DL210_A1.ipynb](assignment-01-sorting-basics/1DL210_A1.ipynb) |
| 2 | Efficient sorting | Merge sort, quick sort, heap sort, and comparisons of quadratic versus `n log n` growth | [1DL210_A2.ipynb](assignment-02-efficient-sorting/1DL210_A2.ipynb) |
| 3 | Hash tables | Hash-table coursework notebook | [1DL210_A3_Group_42.ipynb](assignment-03-hash-tables/1DL210_A3_Group_42.ipynb) |
| 4 | Binary search trees | Recursive insertion, minimum, membership checks, deletion using an in-order successor, and in-order traversal | [1DL210_A4.ipynb](assignment-04-binary-search-trees/1DL210_A4.ipynb) |

### Assignment 4 — Binary Search Trees

The fourth assignment represents a tree using immutable tuples of the form `(key, left, right)`, with `None` representing an empty tree. It includes five functions:

- `insert(t, k)` — insert a new key, preserving the BST ordering invariant.
- `minimum(t)` — find the smallest key.
- `includes(t, k)` — determine whether a key exists.
- `delete(t, k)` — remove a key, including nodes with two children.
- `in_order_walk(t)` — list the keys in sorted order.

The notebook includes the assignment's supplied `unittest` checks. Its code and tests are retained from the uploaded notebook; the presentation was condensed and previously saved execution outputs were cleared. The work-distribution field in the source notebook remains unfilled.

## Repository structure

```text
algorithms-datastructures/
├── assignment-01-sorting-basics/
│   └── 1DL210_A1.ipynb
├── assignment-02-efficient-sorting/
│   └── 1DL210_A2.ipynb
├── assignment-03-hash-tables/
│   └── 1DL210_A3_Group_42.ipynb
├── assignment-04-binary-search-trees/
│   └── 1DL210_A4.ipynb
└── README.md
```

## Running the notebooks

Open any notebook in Jupyter or Google Colab. Run the cells in order so any test scaffolding and previously defined functions are available. Assignment 4 uses Python's standard-library `unittest` module and does not require third-party packages for its included checks.

These files are a record of course exercises rather than a reusable Python package.
