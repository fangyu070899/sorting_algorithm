# sorting_algorithm

## complexity

![image](https://github.com/fangyu070899/sorting_algorithm/blob/main/image/c950295.png)

![image](https://github.com/fangyu070899/sorting_algorithm/blob/main/image/317c55e.png)

### Bubble Sort

Bubble sort compares two adjacent elements and swaps them until they are in the intended order.

Just like the movement of air bubbles in the water that rise up to the surface, each element of the array move to the end in each iteration. Therefore, it is called a bubble sort.

![image](https://github.com/fangyu070899/sorting_algorithm/blob/main/image/bubble-sort-1024x683-2.webp)

### Selection Sort

Selection sort repeatedly selects the smallest (or largest) element from the unsorted portion of the list and swaps it with the first element of the unsorted part. This process is repeated for the remaining unsorted portion until the entire list is sorted.

![image](https://raw.githubusercontent.com/fangyu070899/sorting_algorithm/main/image/1.webp)
![image](https://raw.githubusercontent.com/fangyu070899/sorting_algorithm/main/image/2.webp)
![image](https://raw.githubusercontent.com/fangyu070899/sorting_algorithm/main/image/3.webp)

### Insertion Sort

The array is virtually split into a sorted and an unsorted part. Values from the unsorted part are picked and placed in the correct position in the sorted part.

To sort an array of size N in ascending order iterate over the array and compare the current element (key) to its predecessor, if the key element is smaller than its predecessor, compare it to the elements before. Move the greater elements one position up to make space for the swapped element.

![image](https://raw.githubusercontent.com/fangyu070899/sorting_algorithm/main/image/0_1zi2XtjiLXa3LYZh.webp)

### Merge Sort

Merge sort is a recursive algorithm that continuously splits the array in half until it cannot be further divided i.e., the array has only one element left (an array with one element is always sorted). Then the sorted subarrays are merged into one sorted array.

![image](https://github.com/fangyu070899/sorting_algorithm/blob/main/image/Merge_sort_algorithm_diagram.svg.png)

### Quicksort

The key process in quickSort is a partition(). The target of partitions is to place the pivot (any element can be chosen to be a pivot) at its correct position in the sorted array and put all smaller elements to the left of the pivot, and all greater elements to the right of the pivot.

Partition is done recursively on each side of the pivot after the pivot is placed in its correct position and this finally sorts the array.

![image](https://github.com/fangyu070899/sorting_algorithm/blob/main/image/QuickSort2.png)

### Counting Sort

Counting Sort is a non-comparison-based sorting algorithm that works well when there is limited range of input values. It is particularly efficient when the range of input values is small compared to the number of elements to be sorted. The basic idea behind Counting Sort is to count the frequency of each distinct element in the input array and use that information to place the elements in their correct sorted positions.

![image](https://raw.githubusercontent.com/fangyu070899/sorting_algorithm/main/image/1_lmzbRxK0FNgxzu8owsm4cA.webp)

### Radix Sort

The key idea behind Radix Sort is to exploit the concept of place value. It assumes that sorting numbers digit by digit will eventually result in a fully sorted list. Radix Sort can be performed using different variations, such as Least Significant Digit (LSD) Radix Sort or Most Significant Digit (MSD) Radix Sort.

![image](https://github.com/fangyu070899/sorting_algorithm/blob/main/image/Radix-Sort-in-C-1-768.png)

### Bucket Sort

Create n empty buckets (Or lists) and do the following for every array element arr[i].

Insert arr[i] into bucket[n\*array[i]]
Sort individual buckets using insertion sort.
Concatenate all sorted buckets.

![image](https://github.com/fangyu070899/sorting_algorithm/blob/main/image/what-is-bucket-sort-algorithm.avif)

### Heap Sort

### Shell Sort

# reference

- https://www.programiz.com/dsa/sorting-algorithm
- https://www.hackerearth.com/practice/notes/sorting-and-searching-algorithms-time-complexities-cheat-sheet/
- https://medium.com/austins-software-engineering-journey/insertion-sort-ea0645cc5a23
- https://yuminlee2.medium.com/counting-sort-algorithm-392560fe570e
- https://www.productplan.com/glossary/bubble-sort/
