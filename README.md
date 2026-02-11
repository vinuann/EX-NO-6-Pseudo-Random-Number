# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
{
    int n, i;
    srand(time(0));

    printf("Enter number of random numbers to generate: ");
    scanf("%d", &n);

    printf("Generated random numbers:\n");
    for(i = 0; i < n; i++)
    {
        printf("%d ", rand());
    }

    return 0;
}
```
# OUTPUT:
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/d8fb9ebb-5f40-40a7-b78e-49afd34340bb" />

# RESULT:
Thus, the pseudorandom number generation using the C standard library was successfully implemented.
