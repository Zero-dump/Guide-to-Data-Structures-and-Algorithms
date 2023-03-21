# Guide-to-Data-Structures-and-Algorithms
A short, concentrated description of the main concepts Data Structures and Algorithms

**Array as Fundamental Data Structure**

An **array** is a collection of similar data elements stored at contiguous memory locations - marcked by indexes(counting from 0 in most programing landuages).
Example of array:

![image](https://user-images.githubusercontent.com/67919239/226565491-f02dc8fd-0e35-4be9-b892-673d571943d6.png)

Basic Operations for data structures:

**Read** - looking something up from a particular spot within the data structure. With an array, this would mean looking up a value at a particular index. For example, looking up which grocery item is located at index 2 would be reading from the array.

**Search** - looking for a particular value within a datastructure. With an array, this would mean looking to see if a particular value exists within the array, and if so, which index it’s at. For example,looking to see if “peaches” is in our grocery list, and which index it’s located at would be searching the array.

**Insert** -  adding another value to our data structure. With an array, this would mean adding a new value to an additional slot within the array. If we were to add “figs” to our shopping list, we’d be inserting a new value into the array. 

**Delete** - removing a value from our data structure. With an array, this would mean removing one of the values from the array. For example, if we removed “palms” from our grocery list, that would be deleting from the array.

An **ordered array** is an array data structure in which each element is sorted in numerical, alphabetical, or some other order. That is, every time a value is added, it gets placed in the proper cell so that the values of the array remain sorted. In a standard array, on the other hand, values can be added to the end of the array without taking the order of the values into consideration.

![image](https://user-images.githubusercontent.com/67919239/226609278-166cce3f-925f-4705-b90a-88cea56c804f.png)

**Binary Search** is a searching algorithm used in a sorted array by repeatedly dividing the search interval in half. The idea of binary search is to use the information that the array is sorted and reduce the time complexity to O(Log n). 
