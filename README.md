# Two Sum 🧮

This repository contains my solution to the **Two Sum** problem from LeetCode, implemented in **Python**.

## 📌 Problem

Given an array of integers `nums` and an integer `target`, return the **indices of the two numbers** such that they add up to the target.

You may assume that each input has exactly one solution.

### Example

```text
Input:
nums = [2, 7, 11, 15]
target = 9

Output:
[0, 1]
```

Explanation:

```text
2 + 7 = 9
```

The index of `2` is `0` and the index of `7` is `1`.

## 💻 Solution

```python
class Solution:
    def twoSum(self, nums, target):
        for i in range(len(nums)):
            for j in range(i + 1, len(nums)):
                if nums[i] + nums[j] == target:
                    return [i, j]


solution = Solution()

nums = [2, 7, 11, 15]
target = 9

print(solution.twoSum(nums, target))
```

### Output

```text
[0, 1]
```

## 🧠 Approach

The solution uses two `for` loops.

1. Select one number.
2. Compare it with every number after it.
3. Check whether their sum equals the target.
4. Return the indices when the correct pair is found.

## ⏱️ Complexity

**Time Complexity:** `O(n²)`

Because the program uses two nested loops.

**Space Complexity:** `O(1)`

No additional data structure is used to store the input.

## 🛠️ Technologies Used

* Python 3
* LeetCode
* Visual Studio Code
* Git
* GitHub

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/aishuaishu45793-gif/leetcode5-two-sum.git
```

Open the project:

```bash
cd leetcode5-two-sum
```

Run the Python file:

```bash
python two_sum.py
```

## 📚 What I Learned

* Working with Python lists
* Using `for` loops
* Using indexes
* Comparing values
* Writing functions and classes
* Solving a basic algorithm problem
* Running Python code in VS Code
* Using Git and GitHub

## 🌱 Learning Journey

This repository is part of my journey to learn **Python, Data Structures and Algorithms (DSA), and problem solving** through LeetCode.

More solutions will be added as I continue practicing.

⭐ **Keep learning. Keep coding.**
