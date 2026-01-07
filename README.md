# Maximum-Product-of-Splitted-Binary-Tree.
You are given a binary tree. You must remove exactly one edge so that the tree splits into two subtrees.  👉 Your task is to maximize the product of the sums of the two resulting subtrees.  Return the maximum product modulo (10⁹ + 7).
#  - Maximum Product of Splitted Binary Tree

## 📌 Problem Overview
Given a binary tree, remove exactly one edge to split it into two subtrees.
Return the maximum product of the sums of the two subtrees.

---

## 🧠 Approach
1. Compute total sum of the tree.
2. Use DFS to compute subtree sums.
3. For each subtree, calculate:
   product = subtreeSum × (totalSum - subtreeSum)
4. Track the maximum product.
5. Return result modulo 1e9 + 7.

---

## 🧾 Code
Implemented using **DFS (Depth First Search)** in C++.



## ⏱️ Complexity
- Time: O(N)
- Space: O(H)

---

## 📂 Files
- `solution.cpp` → C++ solution
- `README.md` → Explanation
- `.gitignore` → Ignore compiled files

<hr> 
<h1>🧠 Key Idea (High-Level)</h1>

If we cut an edge, the tree breaks into:

One subtree with sum = subSum

Remaining tree with sum = totalSum - subSum

Product = subSum × (totalSum - subSum)

Try this for every possible subtree and keep the maximum product.
🛠️ Strategy (Step-by-Step)
1. Compute total sum of the tree.
2. Use DFS to compute subtree sums.
3. For each subtree, calculate:
   product = subtreeSum × (totalSum - subtreeSum)
4. Track the maximum product.
5. Return result modulo 1e9 + 7.<br>
<br>
 <hr>
