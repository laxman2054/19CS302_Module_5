# EX 21 C program to calculate the area of a triangle using pointer.
## DATE:
## AIM:
To write a C program to calculate the area of a triangle using pointer.

## Algorithm
1. Start. 
2. Declare three variable value of type float. 
3. Prompt the user to enter  values. 
4. Read the values using scanf. 
5. Find the area of triangle using formula 
6. End.
## Program:
```
#include <stdio.h> 
int main() { 
    float base, height, area; 
    float *pBase = &base, *pHeight = &height; 
    scanf("%f", pBase); 
    scanf("%f", pHeight); 
    area = 0.5 * (*pBase) * (*pHeight); 
    printf("%.2f\n", area); 
}
```
## Output:

![image](https://github.com/user-attachments/assets/d665f55b-5a1d-452f-a8c5-3fc444080b32)


## Result:
Thus the program was executed and the output was verified successfully.
