# merge_sort
## Merge Sort Steps for [16, 21, 11, 8, 12, 22]:
- Step 1:
Split the array into two halves: [16, 21, 11] and [8, 12, 22].
Recursively apply Merge Sort on both halves.

- Step 2:
Split [16, 21, 11] into [16] and [21, 11].
Recursively apply Merge Sort on both halves.
Merge [16] and [11, 21] to get [11, 16, 21].
Split [8, 12, 22] into [8] and [12, 22].
Recursively apply Merge Sort on both halves.
Merge [8] and [12, 22] to get [8, 12, 22].

- Step 3:
Merge [11, 16, 21] and [8, 12, 22] to get [8, 11, 12, 16, 21, 22].

- Step 4:
The final sorted array is [8, 11, 12, 16, 21, 22].

## Big-O Notation:
The time complexity of Merge Sort is O(n log n), where n is the number of elements in the array. The space complexity is O(n) due to the additional space required for merging.