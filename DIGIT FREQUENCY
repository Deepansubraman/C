#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int* nums = (int*) malloc(10 * sizeof(int));
    char c;
    
    for(int i = 0; i < 10; i++)
        *(nums+i) = 0;

    while(scanf("%c", &c) == 1)
        if(c >= '0' && c <= '9')
            (*(nums+(c-'0')))++;
    
    for(int i = 0; i < 10; i++)
        printf("%d ", *(nums+i));
    
    return EXIT_SUCCESS;
}
