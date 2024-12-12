# Extending Quadtrees for Approximate Nearest Neighbor Queries

This repository contains the implementation of a dynamic quadtree data structure for handling spatial queries efficiently. The project extends a static quadtree to support Approximate Nearest Neighbor (ANN) queries, as well as dynamic operations like insertions and deletions.

## Project Overview

Quadtrees are hierarchical data structures widely used in computational geometry and spatial data management. This project focuses on:

- Constructing quadtrees for multi-dimensional data.
- Implementing (1 + ε)-approximate nearest neighbor queries.
- Extending quadtrees to handle dynamic insertions and deletions.
- Analyzing the performance of quadtrees under various conditions.

## Features

1. **Static Quadtree Construction**
   - Efficient organization of multi-dimensional datasets.
   - Calculation of spread and height metrics.

2. **Approximate Nearest Neighbor Queries**
   - Implementation of (1 + ε)-ANN queries for varying ε values.
   - Performance analysis with both fixed and random queries.

3. **Dynamic Operations**
   - **Deletions**: Supports direct deletions and tree reconstruction for efficiency.
   - **Insertions**: Dynamically adapts the tree structure for new data.

4. **Visualization**
   - Generates plots to analyze query performance and approximation trade-offs.

## Requirements

- **Python 3.8+**
- Libraries:
  - `numpy`
  - `matplotlib`

## Dataset

The input dataset consists of:
- The first line containing the dimension `d`.
- Subsequent lines representing points in the d-dimensional space as tuples `(x1, x2, ..., xd)`.

Ensure the dataset is stored in a `.txt` file.

## Usage

### 1. Setup

Clone this repository and install the necessary dependencies:
```bash
pip install -r requirements.txt
