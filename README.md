# Quick-Sort-Visualizer

About: QuickSort is a sorting algorithm that repeatedly divides a data set/structure into halves using a pivot point. The algorithm rearranges the data such that only values greater than that at the pivot wil be on one side, and only values less than on the other. This process is repeated until the data set is sorted. QuickSort is called a "divide and conquer" algorithm because it divides the problem into smaller and smaller problems until they are easy to overcome. QuickSort does nlog(n) time due to its technique of repeatedly dividing the data set in half.

This implementation: This implementation uses the techniques described above. The divide and conquer aspect was taken care of by a partition function which determined exactly where each each sub-array was going to split. The return value of that function was saved in a variable in the actual QuickSort method, and used to partition the array. Recursive calls were made within the main sorting function on the interval of the array from a starting point (index 0, or partition index + 1), to an ending point (partition index - 1, or the end of the array). The items being sorted in this demo are randomly generated shapes being sorted by height.

Demo: https://editor.p5js.org/Hamza_sid/present/vinUsqqJl
