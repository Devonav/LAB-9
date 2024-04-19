# Hash Table Implementation in C

This program demonstrates the implementation of a hash table in C. It reads data from an input file, stores it in a hash table, and then displays the records stored in the hash table.

## Files Included

- `main.c`: Contains the main program logic.
- `input_lab_9.txt`: Sample input file containing records to be stored in the hash table.

## Compilation and Execution

1. Make sure you have a C compiler installed (e.g., GCC).
2. Compile the program using the following command:

```bash
gcc main.c -o hash_table




./hash_table


Hash Function

The hash function used in this implementation is a simple multiplication hashing technique. It calculates the hash value of an integer key based on a constant value.

Data Structures

RecordType: Represents a single record containing ID, name, and order.
HashType: Represents a hash table element containing a pointer to the head of a linked list.

