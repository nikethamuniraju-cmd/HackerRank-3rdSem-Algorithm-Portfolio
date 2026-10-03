
# HackerRank Problem Solving Portfolio

## Student Information

**Name:** Niketha M  
**USN:** R25EF166  
**Semester:** 3rd Semester  
**Branch:** Computer Science and Engineering (CSE)  
**University:** REVA University

### Profiles

- **HackerRank:** [Add your HackerRank profile URL here]
- **GitHub:** https://github.com/nikethamuniraju-cmd

## Introduction

This repository contains my HackerRank problem-solving solutions completed as part of my programming practice and portfolio activities. The problems are solved using C programming, with a focus on understanding algorithms, improving problem-solving skills, and analyzing time and space complexity.

---

# Problems and Solutions

## 1. Mini-Max Sum

### Problem
Find the minimum and maximum values that can be obtained by summing exactly four of five given integers.

### Approach
- Read the five integers.
- Calculate the total sum of all five numbers.
- Find the minimum and maximum values.
- Minimum sum = total sum − maximum value.
- Maximum sum = total sum − minimum value.
- Print both results.

### Time Complexity
**O(n)**, where `n` is the number of elements.

### Space Complexity
**O(1)**

### Alternative Approach
Sort the array first. The sum of the first four elements gives the minimum sum, and the sum of the last four elements gives the maximum sum.

### HackerRank Link
[Mini-Max Sum](https://www.hackerrank.com/challenges/mini-max-sum/problem)

### Screenshot
Add your HackerRank submission screenshot here.

![Mini-Max Sum Screenshot](screenshots/mini-max-sum.png)

---

## 2. Birthday Cake Candles

### Problem
Find how many candles have the maximum height.

### Approach
- Read the candle heights.
- Find the maximum candle height.
- Count how many times the maximum height occurs.
- Return the count.

### Time Complexity
**O(n)**

### Space Complexity
**O(1)**

### Alternative Approach
Sort the candle heights and count the elements equal to the last element of the sorted array.

### HackerRank Link
[Birthday Cake Candles](https://www.hackerrank.com/challenges/birthday-cake-candles/problem)

### Screenshot
Add your HackerRank submission screenshot here.

![Birthday Cake Candles Screenshot](screenshots/birthday-cake-candles.png)

---

## 3. Insertion Sort Part 1

### Problem
Insert the last element of an array into its correct position while maintaining the sorted order of the remaining elements.

### Approach
- Store the last element as the key.
- Compare it with elements before it.
- Shift larger elements one position to the right.
- Insert the key into its correct position.
- Print the array after each shift.

### Time Complexity
**O(n)** for one insertion.

### Space Complexity
**O(1)**

### Alternative Approach
A complete insertion sort can be used to sort the entire array by repeatedly inserting each element into its correct position.

### HackerRank Link
[Insertion Sort Part 1](https://www.hackerrank.com/challenges/insertionsort1/problem)

### Screenshot
Add your HackerRank submission screenshot here.

![Insertion Sort Screenshot](screenshots/insertion-sort-1.png)

---

## 4. Binary Search Tree - Insertion

### Problem
Insert a new value into a Binary Search Tree while maintaining the properties of the BST.

### Approach
- If the root is `NULL`, create a new node.
- If the value is smaller than the root value, insert it into the left subtree.
- If the value is greater than the root value, insert it into the right subtree.
- Return the root of the tree.

### Time Complexity
**O(h)**, where `h` is the height of the tree.

For a balanced BST:

**O(log n)**

For a skewed BST:

**O(n)**

### Space Complexity
**O(h)** due to recursion.

### Alternative Approach
The BST insertion can also be implemented iteratively using a loop instead of recursion.

### HackerRank Link
[Binary Search Tree - Insertion](https://www.hackerrank.com/challenges/binary-search-tree-insertion/problem)

### Screenshot
Add your HackerRank submission screenshot here.

![BST Insertion Screenshot](screenshots/bst-insertion.png)

---

# Summary

| No. | Problem | Approach | Time Complexity | Space Complexity |
|---|---|---|---|---|
| 1 | Mini-Max Sum | Find total, minimum and maximum | O(n) | O(1) |
| 2 | Birthday Cake Candles | Find maximum and count occurrences | O(n) | O(1) |
| 3 | Insertion Sort Part 1 | Shift elements and insert key | O(n) | O(1) |
| 4 | BST Insertion | Recursive tree insertion | O(h) | O(h) |

## Conclusion

These HackerRank problems helped me practice basic algorithms, arrays, sorting, searching, and binary search trees. They also improved my understanding of time and space complexity and strengthened my C programming and problem-solving skills.
