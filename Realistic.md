# COMP 271-SU25 Assignment 1 - Explain. 

## Range of The First Loop:  

In the first loop, for loop will start with the first element of the list and operate up until the element before the "smallest_index" position in the loop. If the first element (in position 0) is the same as the "smallest_index", this loop will not iterate through any part of the array.  

## Range of Second Loop:  

The second loop starts at the element just after the element in the "smallest_index" position and iterates through the rest of the array. If the last element is marked as the "smallest_index", then the for loop will not iterate through the array at all.  

## Diference in Array Positionional Assignments:  

The goal of this program was to identify the smallest element of an array and the remove it from the array. The first loop maps everything from the first loop directly, up until the element before the "smallest_index". When removing that element, the rest of the array elements will not directly map onto the temporary array, but will be one position behind on it. Thus, to compensate for this difference, the indexed element (the way it is coded) will map onto the position one before in the temporary array.