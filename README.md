# Vector Subset Checker

This C++ program checks if one vector is a subset of another by comparing their elements. It is designed to identify whether all elements of the smaller vector exist in the larger vector, regardless of order. The program includes functions to handle vectors of different sizes and ensures an efficient comparison process.

## Features
- Compares two vectors of integers.
- Identifies if the smaller vector is a subset of the larger vector.
- Handles vectors of unequal lengths.
- Uses nested loops for checking element matches between vectors.

## How It Works
- The program first checks which of the two vectors is longer.
- It assigns the longer vector to one variable and the shorter one to another.
- It then iterates through the shorter vector and checks if each element exists in the longer vector.
- If any element of the shorter vector doesn't match an element in the longer vector, the function returns `false`. Otherwise, it returns `true`.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/vector-subset-checker.git
   ```
2. Compile the C++ code:
    g++ -std=c++17 vector-subset-checker.cpp
3. Run the program:
   .\a

## Contributing
Feel free to fork the repository, create a new branch, make changes, and submit a pull request. Any improvements or bug fixes are appreciated!
