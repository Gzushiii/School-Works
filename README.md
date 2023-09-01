# School-Works
CC102T-IT1B

//BSIT-1B
//Raviz, Prince Gian N.
#include <stdio.h>
int main()
{
    int num1, num2, num3;
    int average, quotient, difference;
    printf("Please Enter num1: \n");
        scanf("%d", &num1);
    
    printf("Please Enter num2: \n");
        scanf("%d", &num2);
    
    printf("Please Enter num3: \n");
        scanf("%d", &num3);
        
            //Calculate the average
    average = (num1 + num2 + num3) /3;
    
            //Calculate the quotient
    quotient = num1 / num2;
    
            //Calculate the difference
    difference = num3 - num1;
    
            //Print the results
    printf("The average of %d, %d, and %d is %d\n", num1, num2, num3, average);
    
    printf("The quotient of %d and %d is %d\n", num1, num2, quotient);
    
    printf("The difference of %d and %d is %d\n", num3, num1, difference);

    return 0;
}
