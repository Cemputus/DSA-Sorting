

1. **Insertion Sort**:
   - Time Complexity:
     - Worst-case: O(n^2)
     - Best-case: O(n)
   - Description: Insertion Sort is a simple sorting algorithm that builds the final sorted array one item at a time. It is efficient for small data sets.

2. **Heap Sort**:
   - Time Complexity:
     - Worst-case: O(n log n)
     - Best-case: O(n log n)
   - Description: Heap Sort is an in-place comparison-based sorting algorithm that works by dividing the input into a sorted and an unsorted region and iteratively shrinking the unsorted region.

3. **Counting Sort**:
   - Time Complexity:
     - Worst-case: O(n + k) where k is the range of input values
   - Description: Counting Sort is a non-comparison-based sorting algorithm that works for integers with a limited range of values. It counts the frequency of each value and reconstructs the sorted array.

4. **Comb Sort**:
   - Time Complexity:
     - Worst-case: O(n^2)
     - Best-case: O(n log n)
   - Description: Comb Sort is an improvement over Bubble Sort that eliminates small values at the end of the list efficiently.

5. **Bucket Sort**:
   - Time Complexity:
     - Worst-case: O(n^2) (if each bucket contains multiple values)
     - Best-case: O(n + k) (if each value goes into a separate bucket)
   - Description: Bucket Sort is a distribution-based sorting algorithm that divides the input into buckets and sorts each bucket individually, typically using another sorting algorithm.

6. **Bubble Sort**:
   - Time Complexity:
     - Worst-case: O(n^2)
     - Best-case: O(n)
   - Description: Bubble Sort repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.

7. **Merge Sort**:
   - Time Complexity:
     - Worst-case: O(n log n)
     - Best-case: O(n log n)
   - Description: Merge Sort is a divide-and-conquer algorithm that divides the input array into two halves, recursively sorts them, and then merges the sorted halves.

8. **Quick Sort**:
   - Time Complexity:
     - Worst-case: O(n^2) (rare, can be mitigated with optimizations)
     - Best-case: O(n log n)
   - Description: Quick Sort is a divide-and-conquer algorithm that selects a "pivot" element and partitions the array into two sub-arrays, those less than the pivot and those greater than the pivot. It then recursively sorts the sub-arrays.

9. **Selection Sort**:
   - Time Complexity:
     - Worst-case: O(n^2)
     - Best-case: O(n^2)
   - Description: Selection Sort divides the input into a sorted and an unsorted region. In each iteration, it selects the minimum element from the unsorted region and swaps it with the first element in the unsorted region.
