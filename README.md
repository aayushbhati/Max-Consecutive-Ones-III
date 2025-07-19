# Max Consecutive Ones III

## Problem Description

Given a **binary array** `nums` and an integer `k`, return the **maximum number of consecutive `1`'s** in the array if you can **flip at most `k` `0`'s**.

## Examples

### Example 1:
**Input:**  
`nums = [1,1,1,0,0,0,1,1,1,1,0]`  
`k = 2`  
**Output:**  
`6`  

**Explanation:**  
Flipping two zeros:  
`[1,1,1,0,0,1,1,1,1,1,1]` → longest subarray with consecutive 1's is of length 6.

---

### Example 2:
**Input:**  
`nums = [0,0,1,1,0,0,1,1,1,0,1,1,0,0,0,1,1,1,1]`  
`k = 3`  
**Output:**  
`10`  

**Explanation:**  
Flipping three zeros results in a longest subarray of 10 consecutive 1's.

---

## Constraints
- `1 <= nums.length <= 10⁵`
- `nums[i]` is either `0` or `1`
- `0 <= k <= nums.length`
