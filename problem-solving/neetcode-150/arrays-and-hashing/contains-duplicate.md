# 1. Contains Duplicate

Given an integer array `nums`, return `true` if any value appears **more than once** in the array, otherwise return `false`.

```javascript

Input: nums = [1, 2, 3, 3]

Output: true

```

```javascript
Input: nums = [1, 2, 3, 4]

Output: false

```

## Solutions:

### JavaScript

```javascript
/**
 * @param {number[]} nums
 * @return {boolean}
 */
var containsDuplicate = function(nums) {
    const numsSet = new Set(nums);
    const isEqual = numsSet.size === nums.length;

    return !isEqual;
};

```



