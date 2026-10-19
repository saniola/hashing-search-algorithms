# Hashing & Search Algorithms

Python implementations of a hash table, binary search with upper-bound lookup, and substring search algorithm benchmarking.

## Features

- **task_01.py** — a `HashTable` with chaining for collision resolution, supporting insert/get/delete
- **task_02.py** — binary search over a sorted array of floats that also returns the "upper bound" when the exact value isn't found, plus the iteration count
- **task_03.py** — benchmarks Boyer-Moore, Knuth-Morris-Pratt, and Rabin-Karp substring search algorithms (`boyer_moore.py`, `knuth_morris_pratt.py`, `rabin_karp.py`) against real and fabricated substrings in `text_01.txt` and `text_02.txt`

## Technology

- Python 3

## Running

```
python task_01.py
python task_02.py
python task_03.py
```
