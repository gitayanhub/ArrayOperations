# ArrayOperations
#All-of-these-exercises-are-from-GeeksforGeeks

This repository contains different coding exercises related Array DS

Array Rotataion
Juggling Algorithm approach:

Algorithm description:

Take the length of the array and how many rotations needs to be done. Find out their GCF. Use that GCF value to run the main loop. swap the elements by the numbers of element that we have to rotate for all the elements.

lets say array length is len, rotations to be done is r, so d = gcf(len,r);
we have to move a[l+d] to a[l], where l is a variable which denotes the index of the element to be swapped.


Reversal Algorithm approach:

Reverse the array part by part, first reverse the array from starting index to rotation number index-1, then reverse it from rotation number index to array.length-1. Finally reverse the whole array. This will give us the final result.

Cyclic rotation:

Clockwise cycic rotation can be done by: Taking the first element and store it in a temp variable. Rotate all the elements in the array to the left by one position. Place the temp variable data to the last of the array. Do this process based on how many rotations needs to be done
