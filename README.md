# LeetCode Questions

    This is a collection of questions from LeetCode.com. I have solved most of them and to make it easier for you to find the solutions, I have categorized them into easy, medium, hard and super hard.

    And this is good for you to learn and practice.

    Fork it and make a new branch with your date and solve the problems with index.js file.

    Even I have added launch.json file to run the solutions in vscode. Remember to change the runtimeExecutable path to your node version.

# 1. Array

## 1.a. Move Zeros 
https://leetcode.com/problems/move-zeroes/submissions/1519803526/

![Easy Badge](https://img.shields.io/badge/-Easy-brightgreen)
![Array Badge](https://img.shields.io/badge/-Array-blue)

**Problem**

Given an integer array `nums`, move all `0`'s to the end of it while maintaining the relative order of the non-zero elements.

**Note** that you must do this in-place without making a copy of the array.

    Example 1:
    Input: nums = [0,1,0,3,12]
    Output: [1,3,12,0,0]

    Example 2:
    Input: nums = [0]
    Output: [0]

**Solution**

```js script
const moveZeroes = (nums) => {
    
};
```

## 1.b. Majority Element
https://leetcode.com/problems/majority-element/submissions/1519804367/

![Easy Badge](https://img.shields.io/badge/-Easy-brightgreen)
![Array Badge](https://img.shields.io/badge/-Array-blue)

**Problem**

Given an array `nums` of size `n`, return the majority element.

The majority element is the element that appears more than `⌊n / 2⌋` times. You may assume that the majority element always exists in the array.

    Example 1:
    Input: nums = [3,2,3]
    Output: 3

    Example 2:
    Input: nums = [2,2,1,1,1,2,2]
    Output: 2

**Solution**

```js script
const majorityElement = (nums) => {
    
};
```

## 1.c. Remove Duplicates from Sorted Array
https://leetcode.com/problems/remove-duplicates-from-sorted-array/submissions/1518962336/

![Easy Badge](https://img.shields.io/badge/-Easy-brightgreen)
![Array Badge](https://img.shields.io/badge/-Array-blue)

**Problem**

Given an integer array `nums` sorted in non-decreasing order, remove the duplicates in-place such that each unique element appears only once. The relative order of the elements should be kept the same. Then return the number of unique elements in `nums`.

Consider the number of unique elements of `nums` to be k, to get accepted, you need to do the following things:

 - Change the array `nums` such that the first k elements of `nums` contain the unique elements in the order they were present in `nums` initially. The remaining elements of `nums` are not important as well as the size of `nums`.
 - Return k.

### Custom Judge:


The judge will test your solution with the following code:

    int[] nums = [...]; // Input array
    int[] expectedNums = [...]; // The expected answer with correct length

    int k = removeDuplicates(nums); // Calls your implementation

    assert k == expectedNums.length;
    for (int i = 0; i < k; i++) {
        assert nums[i] == expectedNums[i];
    }

If all assertions pass, then your solution will be accepted.


    Example 1:

    Input: nums = [1,1,2]
    Output: 2, nums = [1,2,_]

    Explanation: Your function should return k = 2, with the first two elements of nums being 1 and 2 respectively.
    It does not matter what you leave beyond the returned k (hence they are underscores).

    Example 2:

    Input: nums = [0,0,1,1,1,2,2,3,3,4]
    Output: 5, nums = [0,1,2,3,4,_,_,_,_,_]

    Explanation: Your function should return k = 5, with the first five elements of nums being 0, 1, 2, 3, and 4 respectively.
    It does not matter what you leave beyond the returned k (hence they are underscores).

**Solution**

```js script
const removeDuplicates = (nums) => {
    
};
```

# 2. String

## 2.a Is Subsequence
https://leetcode.com/problems/is-subsequence/submissions/1519761310/

![Easy Badge](https://img.shields.io/badge/-Easy-brightgreen)
![String Badge](https://img.shields.io/badge/-String-blue)

**Problem**

Given two strings `s` and `t`, return `true` if `s` is a subsequence of `t`, or `false` otherwise.

A **subsequence** of a string is a new string that is formed from the original string by deleting some (can be none) of the characters without disturbing the relative positions of the remaining characters. (i.e., `"ace"` is a subsequence of `"abcde"` while `"aec"` is not).

    Example 1:

    Input: s = "abc", t = "ahbgdc"
    Output: true

    Example 2:

    Input: s = "axc", t = "ahbgdc"
    Output: false

**Solution**

```js script
const isSubsequence = (s, t) => {
    
};
```

## 2.b Valid Palindrome
https://leetcode.com/problems/valid-palindrome/submissions/1519810087/


![Easy Badge](https://img.shields.io/badge/-Easy-brightgreen)
![String Badge](https://img.shields.io/badge/-String-blue)

**Problem**

A phrase is a **palindrome** if, after converting all uppercase letters into lowercase letters and removing all non-alphanumeric characters, it reads the same forward and backward. Alphanumeric characters include letters and numbers.

Given a string `s`, return `true` if it is a palindrome, or `false` otherwise.

    Example 1:

    Input: s = "A man, a plan, a canal: Panama"
    Output: true
    Explanation: "amanaplanacanalpanama" is a palindrome.

    Example 2:

    Input: s = "race a car"
    Output: false
    Explanation: "raceacar" is not a palindrome.

    Example 3:

    Input: s = " "
    Output: true
    Explanation: s is an empty string "" after removing non-alphanumeric characters.
    Since an empty string reads the same forward and backward, it is a palindrome.

**Solution**

```js script
const isPalindrome = (s) => {
    
};
```

