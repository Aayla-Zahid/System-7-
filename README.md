# System 7 Internship – Week 1: Python & Data Science Foundations

**Mentor:** Saad Hassan Saadi
**Focus:** Python basics, NumPy, Pandas, data visualization and a TensorFlow introduction
**Final deliverable:** CSV analysis with charts and summary statistics

Each day's work is in its own folder, with one commit per day.

## Daily progress

| Day | Topics | Folder | Status |
|-----|--------|--------|--------|
| 1 | Python syntax, variables, data types, operators, input/output | `day-01-python-basics` | Pending |
| 2 | Conditions, loops, `range()`, functions | `day-02-control-flow-functions` | Pending |
| 3 | Lists, tuples, dictionaries, sets | `day-03-data-structures` | Pending |
| 4 | File handling, exceptions, modules, basic OOP | `day-04-files-oop` | Pending |
| 5 | NumPy: arrays, indexing, mathematical operations | `day-05-numpy` | Pending |
| 6 | Pandas: Series, DataFrames, filtering, sorting, missing values | `day-06-pandas` | Pending |
| 7 | Matplotlib, Seaborn, TensorFlow intro, CSV analysis task | `day-07-visualization-tensorflow` | Completed |

## What was completed each day

### Day 1 – Python basics
_To be added._

### Day 2 – Control flow and functions
_To be added._

### Day 3 – Data structures
_To be added._

### Day 4 – Files, exceptions and OOP
_To be added._

### Day 5 – NumPy
_To be added._

### Day 6 – Pandas
_To be added._

### Day 7 – Visualization, TensorFlow intro and CSV analysis
**Folder:** `day-07-visualization-tensorflow/`
**Files:** `day-07-visualization-tensorflow.ipynb`, `tested.csv`

**Task 1 (main Week 1 task): CSV analysis with charts and summary statistics**
- Dataset: Titanic passenger records (418 rows, 12 columns).
- Explored the data with Pandas (`head`, `info`, `shape`, data types, duplicates).
- Found missing values in `Age` (86), `Fare` (1) and `Cabin` (327). Filled `Age` and `Fare` with group medians, and replaced `Cabin` with a `HasCabin` column.
- Calculated summary statistics (`describe()`, category counts, survival rates by sex, class, port and cabin).
- Made charts with Matplotlib and Seaborn: survival count, survival by sex, survival rate by class, age histogram by survival, fare box plot by class, age vs fare scatter plot, correlation heatmap, and an age before/after cleaning comparison.
- Wrote conclusions from the results. Note: in this file all women survived and all men did not, which suggests the labels were generated from the `Sex` column.

**TensorFlow introduction**
- Installation, creating scalar, vector, matrix and 3-D tensors, checking shape and dtype.
- Basic tensor operations (add, element-wise multiply, matrix multiply).
- Converted a Pandas column to a tensor.

## How to run
1. Open the notebook in Google Colab or Jupyter.
2. Make sure `tested.csv` is in the same folder (in Colab, upload it when asked).
3. Run all cells.

## Repository structure
```
├── README.md
├── day-01-python-basics/
├── day-02-control-flow-functions/
├── day-03-data-structures/
├── day-04-files-oop/
├── day-05-numpy/
├── day-06-pandas/
└── day-07-visualization-tensorflow/
```
