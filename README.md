## SORTING NUMBER 1 : QUICKSORT
### Quick Sort implementation in C++
Implemented Using vectors in C++ in Codeblocks Ide (MinGW gcc compiler)
#### Header Files Included:
```
 -> iostream
 -> vector
``` 
#### Functions:
```
=> swapp(vector<int>,int,int) 
    ->Swap 2 values of the array(index of elements as parameters)

=> partition
    -> returns the index of correct position of pivot element passed
    
=> quicksort
    ->Recursive function to do the sorting on partitioned vectors
  
=> main
    ->Get the vector from the user, calls the quicksort function on the vector and displays the sorted vector.
