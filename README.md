## Arrays and hashing



## Two Pointers

*2sum:* save a hashmap saving the compliments then iterate in the array until you find the compliment. Complexity: O(n) Time: O(n) 
*3sum:* Complexity: O(n^2) Time: O(1) 
  sort the array, iterate though the array while doing 2sum 
  if sum > 0 then move right pointer to the left, 
  if sum < 0 then move left pointer to the right,
  if sum = 0, To avoid repeating characters move the left pointer to the right until distinct. 
