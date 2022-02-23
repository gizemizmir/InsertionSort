# InsertionSort
## Task1

### [22,27,16,2,18,6]-> Insertion Sort
1. Insertion Sort Phase
```   
[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]
```

2. Big-O Notation 
O(n^2)

3. Time Complexity
Average Case:The number we are looking for is in the middle
O(n^2)
Worst Case:he number we are looking for is at the end
O(n^2)
Best Case:The number we are looking for is at the beginning
O(n)

4. After the sorting array, what is case of 18?
Average Case

### [7,3,5,8,2,9,4,15,6] -> Insertion Sort
Insertion Sort Phase
```
[7,3,5,8,2,9,4,15,6]
[2,3,5,8,7,9,4,15,6]
[2,3,4,8,7,9,5,15,6]
[2,3,4,5,7,9,8,15,6]
[2,3,4,5,6,9,8,15,7]
[2,3,4,5,6,7,8,15,9]
[2,3,4,5,6,7,8,9,15]
```