#include <stdio.h>

int main() {
    int x, y;
    long long result = 1;
    
    printf("Enter x value: ");
    scanf("%d", &x);
    
    printf("Enter y value: ");
    scanf("%d", &y);
    
    while (y > 0) {
        result *= x;
        y--;
    }
    
    printf("Your Answer: %lld", result);
    
    return 0;
}
