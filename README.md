# DSA Question 8 – Merge Sort and Quick Sort

## S3 DSA Assignment

### Aim

To implement Merge Sort and Quick Sort in C, execute them using the given input data, record the number of steps involved, and compare their performance.

---

## 1. Source Code

The following C programs are included in this repository:

- `merge_sort.c` – Implementation of Merge Sort
- `quick_sort.c` – Implementation of Quick Sort

---

## 2. Input Data

The input values used for sorting are provided in:

`input.txt`

The same input data is used to test both sorting algorithms for comparison.

---

## 3. Output

The sorted results obtained from the programs are stored in:

`output.txt`

The output shows the elements after applying the sorting algorithms.

---

## 4. Trace Table

The step-by-step execution of the sorting process is recorded in:

`trace_table.md`

The trace table shows the changes made to the elements during sorting.

---

## 5. Merge Sort

Merge Sort is a divide-and-conquer sorting algorithm.

### Working

1. The array is divided into two halves.
2. Each half is recursively divided until single elements remain.
3. The smaller sorted arrays are merged.
4. The process continues until the complete array is sorted.

### Complexity

| Case | Time Complexity |
|------|-----------------|
| Best Case | O(n log n) |
| Average Case | O(n log n) |
| Worst Case | O(n log n) |

Space Complexity: O(n)

---

## 6. Quick Sort

Quick Sort is also a divide-and-conquer sorting algorithm.

### Working

1. A pivot element is selected.
2. The array is partitioned around the pivot.
3. Elements smaller than the pivot are placed on one side.
4. Elements greater than the pivot are placed on the other side.
5. The same process is repeated recursively for the sub-arrays.

### Complexity

| Case | Time Complexity |
|------|-----------------|
| Best Case | O(n log n) |
| Average Case | O(n log n) |
| Worst Case | O(n²) |

Space Complexity: O(log n) on average due to recursion.

---

## 7. Step Count

The number of steps involved in the algorithms is recorded and compared using the given input data.

The step-count information is available in:

- `comparison.txt`
- `merge_sort.txt`
- `merge_trace.txt`

---

## 8. Comparison Table

The comparison between Merge Sort and Quick Sort is provided in:

`comparison_table.md`

| Feature | Merge Sort | Quick Sort |
|---------|------------|------------|
| Technique | Divide and Conquer | Divide and Conquer |
| Best Case | O(n log n) | O(n log n) |
| Average Case | O(n log n) | O(n log n) |
| Worst Case | O(n log n) | O(n²) |
| Extra Space | O(n) | O(log n) average |
| Stable | Yes | Generally No |

---

## 9. Complexity Analysis

The detailed complexity analysis is available in:

`complexity.txt`

Merge Sort provides O(n log n) time complexity in the best, average, and worst cases.

Quick Sort provides O(n log n) average-case time complexity, while its worst-case time complexity is O(n²), depending on the choice of pivot.

---

## 10. Files Included

| File | Description |
|------|-------------|
| `merge_sort.c` | Merge Sort source code |
| `quick_sort.c` | Quick Sort source code |
| `input.txt` | Input data |
| `output.txt` | Sorted output |
| `merge_trace.txt` | Merge Sort trace |
| `merge_sort.txt` | Merge Sort details |
| `complexity.txt` | Complexity analysis |
| `comparison.txt` | Algorithm comparison |
| `trace_table.md` | Trace table |
| `comparison_table.md` | Comparison table |
| `README.md` | Project documentation |

---

## Conclusion

Merge Sort and Quick Sort were successfully implemented in C and tested using the given input data. Both algorithms use the divide-and-conquer technique. Merge Sort has a consistent O(n log n) time complexity, while Quick Sort has O(n log n) average-case complexity and O(n²) worst-case complexity. The step counts, trace table, complexity analysis, and comparison are included in this repository for reference.
