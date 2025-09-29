# Value-Swapping
Write a program in C to get value before swapping the value?
#include <stdio.h>

int main() {
    int a=5,b=10,c;
    printf("your value before swapping");
    
    printf("value of a is %d ",a);
    printf("value of b is %d",b);
    
    c=a;
    a=b;
    b=c;
    
    printf("your value after  swapping");
    printf("value of a is %d and value of b is %d",a,b);

}
