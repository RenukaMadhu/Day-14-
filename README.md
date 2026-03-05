This C program checks whether a number entered by the user is even or odd.
If the number is divisible by 2, the program prints 1 (true) which means the number is even.
If the number is not divisible by 2, it prints 0 (false) which means the number is odd.
Explanation
1. #include <stdio.h>
This header file is used for input and output functions like printf() and scanf().
2. #include <math.h>
This header file is used for mathematical functions. In this program it is not required but it does not affect the execution.
3. int main()
This is the main function where the execution of the program starts.
4. int x;
A variable x is declared to store the number entered by the user.
5. printf("enter a number");
This statement prints a message asking the user to input a number.
6. scanf("%d",&x);
This statement reads the integer value entered by the user and stores it in the variable x.
7. printf("%d", x % 2 == 0);
This line checks whether the number is even or odd.
% is the modulus operator, which gives the remainder.
x % 2 finds the remainder when x is divided by 2.
Condition:
If the remainder is 0, the number is even.
If the remainder is not 0, the number is odd.
The expression x % 2 == 0 returns:
1 (true) if the number is even
0 (false) if the number is odd

8. return 0;
This statement ends the program and indicates successful execution.
