# Binary Search

## Challenge
Write a function that takes in 2 parameters, a sorted array and a search key. Use binary search method to return the index of the array's element that matches the search key, or return –1 if the element does not exist  

## Approach & Efficiency
Take in sorted array and search value 

Determine length of the incoming array 

Determine the index of the midpoint 

Capture the value of the midpoint 

Compare midpoint to search value 

If the search value is less than the midpoint find the midpoint between the beginning of the array and the original midpoint. 

New Midpoint = currentIdx/2 

If the search value is greater than the midpoint, find the midpoint between the original midpoint and the end of the array. 

New Midpoint = (ArrLength – currentIdx/2) + currentIdx 

 

Repeat process until value is found, or the whole array has been searched. 

If value is found return index of value 

If value is not found return -1 

#### Big O:
Time: O(n);
Space: O(1);

## Solution
