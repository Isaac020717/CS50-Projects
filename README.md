# Mario Set 1

#include <cs50.h>
#include <stdio.h>


int main(void)
{
    
    //First We Get The Height of The Pyramid
    int height = get_int("ENTER A HEIGHT : ");
    printf("\n");
    
    // This Loop Prints All Rows
    for (int i = 0; i<height; i++)
    {
        // Print Spaces
        for (int s = 0; s<(height-i); s++)
        {
            printf(" ");
        }
        
        // Print Left Side
        for (int lt = 0; lt<=i; lt++)
        {
            printf("#");
        }
        
        // Put Spacing Between Sides
        printf("  ");
        
        // Print Right Side
        for (int rt = 0; rt<=i; rt++)
        {
            printf("#");
        }
        
        // New Line
        printf("\n");
        
    }
    
}
