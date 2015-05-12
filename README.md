#include <stdio.h>
int main(){
     int oper;
     int num1=8;
     int num2=3;
     int num3=5;
     oper= num1 + num2 + num3;
     oper= (oper-num1)*num2;
     oper= (oper-num1)-num1;
     oper= (oper+num1)*num2;
     oper= (oper-num1)/num2--;
     oper= oper-num3;
     oper= oper ++;
     oper= oper+num1;
     printf("\n el numero sera por siempre %d \n",oper);
     
}     
     
