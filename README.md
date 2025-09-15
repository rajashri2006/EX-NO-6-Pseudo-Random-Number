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

int main() {
   
    srand(time(0));

    int n;
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &n);

    printf("Generated random numbers:\n");
    for (int i = 0; i < n; i++) {
        int random_number = rand();
        printf("%d\n", random_number);
    }

    return 0; 
}

```

# OUTPUT:

<img width="807" height="332" alt="image" src="https://github.com/user-attachments/assets/72e03487-7361-463c-a90e-1935fd904bf4" />



# RESULT:

Thus the implementation of Pseudorandom Number Generation Using Standard library is executed successfully.
