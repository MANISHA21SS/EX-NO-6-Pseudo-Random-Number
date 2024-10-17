# EX-NO-6-Pseudo-Random-Number

# AIM: 

Implementation of Pseudorandom Number Generation Using Standard library

# PROGRAM:
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() 
{
    int count, min, max;
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &count);
    printf("Enter the minimum value: ");
    
    scanf("%d", &min);
    printf("Enter the maximum value: ");
    scanf("%d", &max);
    srand(time(NULL));
    printf("Pseudorandom numbers:\n");   
    for (int i = 0; i < count; i++) 
    {
        int random_number = (rand() % (max - min + 1)) + min;
        printf("%d\n", random_number);
    }
    return 0;
}
# OUTPUT:
![Screenshot (193)](https://github.com/user-attachments/assets/0005eac9-2fc6-45be-92bb-5a0c3db418a8)

# RESULT:
Thus,
Implementation of Pseudorandom Number Generation Using Standard library is executed successfully.

