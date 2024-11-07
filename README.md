#include <stdio.h>



int main() {

    // Step 1: Define and initialize a 2D array named scores

    int scores[2][2] = {

        {85, 90},

        {78, 88}

    };



    // Step 2: Print the elements of the array using a nested for loop

    printf("Elements of the 2D array 'scores':\n");

    for (int i = 0; i < 2; i++) {           // Loop through rows

        for (int j = 0; j < 2; j++) {       // Loop through columns

            printf("scores[%d][%d] = %d\n", i, j, scores[i][j]);

        }

    }



    return 0;

}

