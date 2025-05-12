# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1. Start the program
2. Read the input number from the user
3. Initialize sum = 0
4. Using a do while loop
5. Repeat the loop until num becomes 0
6. Display the sum
7. End.

## Program:
```
#include <stdio.h>
int main()
{
    int num, digit, sum = 0;
    scanf("%d", &num);
    int temp = num; 
    do
{
        digit = num % 10;
        if (digit % 2 != 0)
 {
            sum += digit;
        }
        num /= 10;
    } while (num != 0);
    printf("Sum of odd digits of %d is: %d\n", temp, sum);
    return 0;
}
```

## Output:
![WhatsApp Image 2025-05-12 at 19 54 39_5da3fce0](https://github.com/user-attachments/assets/d1577b95-37c2-497b-89c7-16ecb93cbd08)


## Result:
Thus the program was executed and the output was verified successfully.
