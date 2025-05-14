# Day15-50-days-coding-challenge

Welcome to Day 15 of the #DrGViswanathanChallenge!  
Today’s focus was on handling linked lists and number-to-string conversions. Here are the problems and my solutions:

---

## 🔢 Problem 1: Add Two Numbers (Linked List)
**Problem Statement:**  
You are given two non-empty linked lists representing two non-negative integers.  
The digits are stored in **reverse order**, and each of their nodes contains a **single digit**.  
Add the two numbers and return the sum as a linked list.

### ✅ Example:
- Input: `l1 = [2,4,3]`, `l2 = [5,6,4]`  
  Output: `[7,0,8]` → 342 + 465 = 807

### 💡 Approach:
- Traverse both lists node-by-node.
- Keep track of carry while summing.
- Create a new linked list to store the result.

---

## 🔠 Problem 2: Excel Sheet Column Title
**Problem Statement:**  
Given an integer `columnNumber`, return its corresponding column title as it appears in Excel.

### ✅ Example:
- Input: `1` → Output: `"A"`  
- Input: `28` → Output: `"AB"`  
- Input: `701` → Output: `"ZY"`

### 💡 Approach:
- Simulate base-26 conversion.
- Use `chr(ord('A') + (n - 1) % 26)` and adjust for 1-indexed logic.
