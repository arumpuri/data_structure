# Sorting Algorithms in Data Structures and Algorithms

Sorting algorithms arrange data in a specific order (ascending or descending) to enhance the efficiency of other operations like searching or merging. Below is an explanation of commonly used sorting algorithms:

---

## 1. Bubble Sort
- **Description**: Repeatedly compares adjacent elements and swaps them if they're in the wrong order.
- **Time Complexity**: 
  - Best: `O(n)` (when the array is already sorted)
  - Average/Worst: `O(n^2)`
- **Space Complexity**: `O(1)`
- **Use Case**: Simple but inefficient for large datasets.

---

## 2. Selection Sort
- **Description**: Repeatedly finds the minimum element and places it at the correct position.
- **Time Complexity**: `O(n^2)` for all cases.
- **Space Complexity**: `O(1)`
- **Use Case**: Useful when memory write operations are costly.

---

## 3. Insertion Sort
- **Description**: Builds the sorted list one element at a time by inserting each element into its correct position.
- **Time Complexity**: 
  - Best: `O(n)` (for nearly sorted data)
  - Average/Worst: `O(n^2)`
- **Space Complexity**: `O(1)`
- **Use Case**: Efficient for small or nearly sorted datasets.

---

## 4. Merge Sort
- **Description**: Divides the array into halves, sorts them recursively, and merges the sorted halves.
- **Time Complexity**: `O(n log n)` for all cases.
- **Space Complexity**: `O(n)`
- **Use Case**: Suitable for large datasets but requires additional memory.

---

## 5. Quick Sort
- **Description**: Selects a pivot, partitions the array around the pivot, and recursively sorts the partitions.
- **Time Complexity**: 
  - Best/Average: `O(n log n)`
  - Worst: `O(n^2)` (when the pivot selection is poor)
- **Space Complexity**: `O(log n)` (for recursive stack)
- **Use Case**: Fast and widely used; suitable for in-place sorting.

---

## 6. Heap Sort
- **Description**: Builds a max heap (or min heap) and repeatedly extracts the root to sort the array.
- **Time Complexity**: `O(n log n)` for all cases.
- **Space Complexity**: `O(1)`
- **Use Case**: In-place sorting with no additional memory requirement.

---

## 7. Radix Sort
- **Description**: Non-comparative algorithm that sorts elements digit by digit using counting sort as a subroutine.
- **Time Complexity**: `O(d * (n + k))`, where `d` is the number of digits, `n` is the number of elements, and `k` is the range of the digits.
- **Space Complexity**: `O(n + k)`
- **Use Case**: Best for integers or strings with fixed lengths.

---

## 8. Counting Sort
- **Description**: Counts the frequency of each element and uses this information to place elements in sorted order.
- **Time Complexity**: `O(n + k)`, where `k` is the range of input values.
- **Space Complexity**: `O(n + k)`
- **Use Case**: Efficient for small ranges of integers.

---

## 9. Bucket Sort
- **Description**: Divides elements into buckets, sorts each bucket individually, and combines them.
- **Time Complexity**: 
  - Best: `O(n + k)`
  - Average: `O(n + n log n)`
  - Worst: `O(n^2)` (if all elements fall into one bucket)
- **Space Complexity**: `O(n + k)`
- **Use Case**: Works well with uniformly distributed data.

---

## 10. Shell Sort
- **Description**: Improves insertion sort by comparing elements far apart and reducing the gap gradually.
- **Time Complexity**: `O(n log^2 n)` (varies based on gap sequence).
- **Space Complexity**: `O(1)`
- **Use Case**: More efficient than insertion sort for large datasets.

---

