# EX-11-EMI-CALCULATOR

## AIM

To write a program to prepare EMI calculator using function without return type and with arguments.

## ALGORITHM

1.	Start the program.
2.	Read principal amount, rate of interest and months.
3.	Pass these values as arguments to function.
4.	Calculate EMI using the formula, amt=(prpow(1+r,t))/(pow(1+r,t)-1)
5.	Display the result.
6.	Stop the program.

## PROGRAM
      #include <stdio.h>
      #include <math.h>
      void calc(float p,float r,int t)
      {
      r=r/(12*100);
      float emi=(p*r*pow(1+r,t))/(pow(1+r,t)-1);
      printf("Monthly EMI is= %.3f",emi);
      }
      int main(){
         float p,r;
         int m;
         printf("Enter the principal amount : ");
         scanf("%f",&p);
         printf("Enter the rate : ");
         scanf("%f",&r);
         printf("Enter the number of months : ");
         scanf("%d",&m);
         calc(p,r,m);
         return 0;
    }

## OUTPUT
![11](https://github.com/user-attachments/assets/6458a7b6-cc1d-4fa0-b15b-af81ce6276d7)






## RESULT

Thus the program to prepare EMI calculator using function without return type with arguments has been executed successfully
 
 


# EX-12-FIBONACCI-SERIES
## AIM
To write a C program to generate the Fibonacci series for the value 6.

## ALGORITHM
1.	Start the program.
2.	Read number of terms to display.
3.	Add the previous two terms and store it in new term.
4.	Assign 2nd term to 1st term and 3rd term to 2nd term.
5.	Repeat steps 3 and 4 n number of times.
6.	Display the result.
7.	Stop the program.

## PROGRAM
     #include <stdio.h>
     int main() {
       int n;
       printf("Enter the number : ");
       scanf("%d",&n);
       int first=0,second=1,next;
       for(int i=1;i<=n;i++) {
           printf("%d ",first);
           next=first+second;
           first=second;
           second=next;
      }
    }
## OUTPUT


![12](https://github.com/user-attachments/assets/47d955c7-ab5c-45b8-bfcd-b079ecd36420)







## RESULT
Thus the program to generate the Fibonacci series for the value 6 has been executed successfully.
 
 


# EX-13-ONE-DIMENSIONAL-ARRAY
## AIM
To write a C program to read n elements as input and print the last element of the array.

## ALGORITHM
1.	Start the program.
2.	Read a variable.
3.	Read the array values n number of times.
4.	Print the last element.
5.	Stop the program.

## PROGRAM
     #include <stdio.h>
     int main() {
       int n,i;
       printf("Enter the number : ");
       scanf("%d",&n);
       int a[n];
       for(i=0;i<n;i++) {
           scanf("%d",&a[i]);
        
     }
      printf("The last element in array is: %d\n",a[n-1]);
    
      return 0;
    }
## OUTPUT

![13](https://github.com/user-attachments/assets/9e6ba069-6360-4716-abe8-1d665aadc1a8)









## RESULT
Thus the program to read n elements as input and print the last element of the array has been executed successfully.
 
 


# EX-14-POSITIVE-ARRAY-ELEMENTS
## AIM
To write a C Program to count total number of positive elements in an array.

## ALGORITHM
1.	Start the program.
2.	Read a variable.
3.	Read the array values n number of times.
4.	If the array value can be divided by 2 then increment count by 1.
5.	Display result.
6.	Stop the program.

## PROGRAM
     #include <stdio.h>
     int main() {
       int n,i;
       int count=0;
       printf("Enter a number : ");
       scanf("%d",&n);
       int a[n];
       for(i=0;i<n;i++) {
           scanf("%d",&a[i]);
           if(a[i]>0) {
              count++;
        }
    }
     printf("The number of positive elements in array = %d",count);
    }

## OUTPUT


![14](https://github.com/user-attachments/assets/300b8262-04a7-40a3-8af9-8c394b1fe949)




## RESULT
Thus the program to count total number of positive elements in an array has been executed successfully.





 
 


# EX -15 - Replace All Even Elements With 'E' In One Dimensional Array

## Aim:
To write a C program to replace all even elements with 'E' in one dimensional array

## Algorithm:
1.	Input the array:
  Read the size of the array.
  Input the elements of the array.
2.	Iterate through the array:
 	For each element of the array, check if the element is even (i.e., if the element modulo 2 equals 0).
3.	Replace even elements with 'E':
     If an element is even, replace that element with the character 'E'.
4.	Output the updated array:
 Print the updated array after replacements.

## Program:
    #include <stdio.h>
    int main() {
       int n,i;
       printf("Enter the number : ");
       scanf("%d",&n);
       int a[n];
       for(i=0;i<n;i++) {
           scanf("%d",&a[i]);
           if(a[i]%2==0) {
              printf("E ");
        }  else{
              printf("%d ",a[i]);
        }
    }
      return 0;
    
    }
## Output:
 ![15](https://github.com/user-attachments/assets/1f121756-4c62-4588-aae2-22732adb2518)




## Result:

Thus, the program to replace all even elements with 'E' in one dimensional array was verified successfully.



