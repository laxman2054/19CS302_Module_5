# EX 22 C program to count total number of even elements in an array using calloc().
## DATE: 07-05-2025
## AIM:
To write a C program to count total number of even elements in an array using calloc().

## Algorithm:
1. Start.
2. Define a variables.
3. Write program to count total number of even elements in an array using calloc().
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.

## Program:
```c program
#include<stdio.h> 
#include<stdlib.h> 
int main()
{
int *arr,n,i,count=0; 
scanf("%d",&n); 
arr=(int*)calloc(1,sizeof(int)); 
for(i=0;i<n;i++)
{
scanf("%d",&arr[i]);
}
for(i=0;i<n;i++)
if(arr[i]%2==0) 
count++;
printf("Total even elements: %d",count);
}
```

## Output:
![image](https://github.com/user-attachments/assets/fc17064a-f203-40f7-be85-cfac3550bfbc)


## Result:
Thus the program was executed and the output was verified successfully.
