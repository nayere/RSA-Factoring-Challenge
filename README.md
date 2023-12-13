# RSA-Factoring-Challenge
Function factorize:
Takes an integer value as input and finds its factors using a basic algorithm.
Starts i at 2 and iterates through values of i until it finds the first factor of value.
Prints the factorization in a specific format.

Argument Check:
Checks if the number of command-line arguments is not equal to 2, and if so, exits the program.

Reading File: 
Tries to open a file whose name is provided as the first argument (argv[1]). If successful, it reads lines from the file one by one.
It converts each line to an integer and calls the factorize function on that integer.
