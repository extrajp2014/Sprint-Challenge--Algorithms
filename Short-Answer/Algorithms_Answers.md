#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) because (n^3) outer loop divide by (n^2) inner variable expansion is (n)

b) O(nlogn) because outer loop runs (n) time and inner loop run at log2 (n)


c) O(n) because the recursive function call (n) time.

## Exercise II

- Let the starting point equals to the middle position of n-story building.
Test drop the egg at starting point:
- If the egg breaks, change the starting point to the bottom middle position of our tested starting point. Go back and repeat test drop.
- If the egg does not break, change the starting point to the top middle position of our tested starting point. Go back and repeat test drop.
- Repeat the process until we find the position where the egg first start to break.

- O(log(n)) runtime because the operations are cut in half at each repetition to minimize the number of dropped + broken eggs.