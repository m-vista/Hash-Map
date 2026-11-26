# Hash Map Implementation

This project was developed for CS261 – Data Structures at Oregon State University. It implements two hash maps in Python using different collision resolution techniques.

## Implementations

- **Separate Chaining:** Uses linked lists to store entries that hash to the same bucket.
- **Open Addressing:** Uses quadratic probing to resolve collisions and tombstones to handle deleted entries.

## Features

- Insertion, retrieval, updating, and removal of key-value pairs
- Dynamic resizing and rehashing
- Load factor calculation
- Prime-number table capacities
- Hash map iteration (open addressing)
- Finding the mode and frequency of elements in a dynamic array

## Files

- `hash_map_sc.py` – Separate chaining implementation
- `hash_map_oa.py` – Open addressing implementation
- `include.py` – Supporting data structures and hash functions

## Running the Program

Both implementations include example test cases that can be run using Python 3.

```bash
python3 hash_map_sc.py
python3 hash_map_oa.py
```

## Acknowledgments

Starter code and supporting data structures were provided by Oregon State University as part of CS261.
