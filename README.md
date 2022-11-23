# [Patika.dev](https://www.patika.dev/) Sorting Project 2
**[16,21,11,8,12,22]**

1. Write the steps of the array given above according to the **merge sort**.
2. Write **Big-O notation**.

### **1-**
* Divide the unsorted array into subarray, each containing a single element.
* Take adjacent pairs of two single-element array and merge them to form an array of 2 elements.
* Repeat the process till a single sorted array is obtained.

*Step 1* : [16,21,11]-[8,12,22] \
*Step 2* : [16]-[21,11]-[8,12]-[22] \
*Step 3* : [16]-[21]-[11]-[8]-[12]-[22] \
*Step 4* : [16]-[11,21]-[8,12]-[22] \
*Step 5* : [11,16,21]-[8,12,22] \
*Step 6* : **[8,11,12,16,21,22]** (Sorted Array)

### **2-**

Big-O = O(nlogn)