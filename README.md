# IF a five digit number is input through the keyboard,write a c porgram to calculate the sum of its digits

#include<stdio.h>
int main(){

  int digit;
  printf("Enter a number whose sum you want\n");
  scanf("%d",&digit);

  int mod=0,div;

  div=digit;
  while(div!=0){

    mod=div%10+mod;
    div=div/10;

  }

  printf("Sum of digits of that number is %d",mod);
}
