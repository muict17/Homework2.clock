# Homework2.clock
6288222#include <stdio.h> 
int main() 
{ 
    int h,m;
    scanf("%d %d",h,m);
    if (h == 12) h = 0; 
    if (m == 60) m = 0; 
     h = 0.5 * (h*60 + m); 
     m = 6*m; 
    int angle = (h - m);
    angle = (360-angle); 
    printf("%d",angle);
  
    return 0;
} 

