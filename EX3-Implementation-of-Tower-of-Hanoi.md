# EX3 Implementation of Tower of Hanoi
## DATE: 28-04-25
## AIM:
To write a C program to implement Tower of Hanoi

## Algorithm
1. Start the program. 
2. Define the priority() function to return the priority of operators. 
3. Initialize the string containing operators and operands. 
4. Loop through each character in the string. 
5. For each operator, call the priority() function to determine its priority. 
6. Print the operator and its corresponding priority level. 
7. End.  

## Program:
```
/*
Program to implement Tower of Hanoi
Developed by: shrenidhi
RegisterNumber:  212223040196
*/

#include<stdio.h> 
void TOH(int n,char x,char y,char z) 
{ 
if(n>0) 
{ 
TOH(n-1,x,z,y); 
printf("%c to %c",x,y); 
printf("\n"); 
TOH(n-1,z,y,x); 
} 
} 
int main() 
{ 
int n=2; 
TOH(n,'A','B','C'); 
}


```


## Output:
![image](https://github.com/user-attachments/assets/6ce5cd1c-7e0e-4a31-86fd-580af89a304f)



## Result:
Thus, the C program to implement Tower of Hanoi using recursion is implemented successfully.
