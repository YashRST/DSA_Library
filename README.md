# Project Name

## Features

### Sorting Algorithms
Implements various sorting algorithms such as:
- Binary Insertion Sort
- Bubble Sort
- Cocktail Sort
- Heap Sort
- Insertion Sort
- Linear Sort
- Merge Sort
- Quick Sort
- Selection Sort

### Data Structures
Includes the following data structures:
- Doubly Linked List
- Singly Linked List
- Stack
- Queue

### Utility Functions
General-purpose utility functions for assisting in sorting and data structure manipulation.

## How to Build
To build the static library and test cases, follow these steps:

1. Navigate to the root of the project directory.
2. Compile the library and source files using a C compiler. For example, you can use `gcc` to build the library:
    ```bash
    gcc -c src/*.c -Iinclude
    ar rcs lib/DSLib.lib *.o
    ```
3. To compile the test cases, you can use the following command:
    ```bash
    gcc testCase/binaryInsertionSortTest.c -o testCase/binaryInsertionSortTest -Iinclude -Llib -lDSLib
    ```
4. Repeat the process for each test case.

## How to Run Tests
After building the test cases, navigate to the `testCase` directory and run the executables to verify the functionality of the corresponding algorithm or data structure.

For example, to run the test for binary insertion sort, use:
```bash

./binaryInsertionSortTest.exe
```
you should see the output indicating the result of the tests.

## Contributions
Contributions to the project are welcome! Feel free to fork the repository and submit pull requests. Please ensure that your code adheres to the project’s coding style and that all tests pass.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
