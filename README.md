#include<stdio.h>
int main(){
    double Celsius;
    double Fahrenheit;
    
   puts("Please enter the celsius temprature value");
    scanf("%lf",&Celsius);
    
   Fahrenheit= ((Celsius* 9.0 / 5.0) + 32.0);
   
   puts("The temprature in Fahrenheit is:");
   printf("%.4lf",Fahrenheit);
   
   return 0;
}
