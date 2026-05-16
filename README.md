# EX-NO-6-Pseudo-Random-Number
## Name: Titus Ratna Kumar Karivella
## Reg no: 212224230292

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
int i, n; 
srand(time(0)); 
printf("Enter how many pseudorandom numbers you want to generate: "); 
scanf("%d", &n); 
printf("Generating %d pseudorandom numbers between 0 and 99:\n", n); 
for (i = 0; i < n; i++) { 
int randomNumber = rand() % 100; 
printf("%d ", randomNumber); 
} 
printf("\n"); 
return 0; 
}
```
# OUTPUT:

<img width="811" height="251" alt="image" src="https://github.com/user-attachments/assets/442a0ee4-13c4-4410-8a6c-eb9a0e25a4ef" />

# RESULT:
Hence the experiment has been executed successfully
