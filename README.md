# MarioBlock
I'm trying to create a code which lets the user decide the size (height) of the block. 


#include <cs50.h>
#include <stdio.h>

int main(void)
{
    int n;
    do {
        n = get_int("Size: ");
    }
    while (n < 1);


    for(int i = 0; i < n; i++) {
        printf("#");
        for (int j = 0; j < n; j++) {
            printf("#");
        }
        printf("\n");
    }
    printf("\n");
}

---------
on the terminal 


mario-less/ $ make mario
mario-less/ $ ./mario
Size: 5
######
######
######
######
######

mario-less/ $ 

// this is what I have so far.. 

