# 📘 Leetcode Practice

A collection of Python solutions to LeetCode problems. This repository is part of my learning journey to strengthen algorithmic thinking and prepare for technical interviews.

---

## 📂 Folder Structure

```
leetcode-practice/
├── 001-two-sum.py
├── 021-merge-two-sorted-lists.py
├── 121-best-time-to-buy-sell-stock.py
├── 242-valid-anagram.py
...
```

Each solution includes:
- Problem link
- Approach explanation
- Clean, commented code

---

## ✅ Topics Covered

- Arrays & Strings  
- Hash Tables  
- Linked Lists  
- Sliding Window  
- Two Pointers  
- Sorting & Searching  
- Dynamic Programming (coming soon)

---

## ✏️ Example Format in Each File

```python
# LeetCode 1: Two Sum
# https://leetcode.com/problems/two-sum/
# Time Complexity: O(n)
# Space Complexity: O(n)

def twoSum(nums, target):
    seen = {}
    for i, num in enumerate(nums):
        diff = target - num
        if diff in seen:
            return [seen[diff], i]
        seen[num] = i
```

---

## 📈 Why This Repo?

I’m practicing daily to:
- Improve coding problem-solving skills
- Build consistency for interviews
- Share learning publicly

---

## 🔗 Connect

- 🧑‍💻 Resume: [[Link Here](https://www.linkedin.com/in/chia-en-tsai-0a9336ab)]
- 📫 Email: [vbn20505h94ru8p@gmail.com](mailto:vbn20505h94ru8p@gmail.com)
