---
slug: /silver/binary-search
title: "Binary Search"
author: Nathan Chen
order: 4
prerequisites: 
 - 
     - Silver - Sorting
---

Binary search can be used on monotonic functions for a logarithmic runtime.

<!-- END DESCRIPTION -->

## The Basic Application

"Find an element in a sorted array in O(log N) time." This is a very basic form of binary search. Other variations are similar, like "Given K, find the largest element less than K in a sorted array."
### Tutorial
- [GeeksForGeeks](https://www.geeksforgeeks.org/binary-search/)
- [Wikipedia](https://en.wikipedia.org/wiki/Binary_search_algorithm)
### Library Functions to do Binary Search:
#### Java
 - [Arrays.binarySearch](https://docs.oracle.com/javase/7/docs/api/java/util/Arrays.html)
 - [Collections.binarySearch](https://docs.oracle.com/javase/7/docs/api/java/util/Collections.html)
#### C++
 - [lower_bound](http://www.cplusplus.com/reference/algorithm/lower_bound/)
 - [upper_bound](http://www.cplusplus.com/reference/algorithm/upper_bound/)
### Problems
 - [USACO Silver Counting Haybales](http://www.usaco.org/index.php?page=viewproblem2&cpid=666)
 
 ## Binary Searching on the Answer
 Oftentimes used when you need to find the minimum or maximum of some quantity such that it satisfies some property.
 
  ### Tutorial
  - [CPH Section 12.1](https://www.overleaf.com/project/5e73f65cde1d010001224d8a)
### Problems
- [USACO Silver Cownvention](http://www.usaco.org/index.php?page=viewproblem2&cpid=858)
- [USACO Silver Cow Dance](http://www.usaco.org/index.php?page=viewproblem2&cpid=690)
- [USACO Silver Social Distancing](http://www.usaco.org/index.php?page=viewproblem2&cpid=1038)
- [USACO Silver Loan Repayment](http://www.usaco.org/index.php?page=viewproblem2&cpid=991)
	- Also needs some math and "sqrt" analysis
- [USACO Silver Angry Cows](http://usaco.org/index.php?page=viewproblem2&cpid=594)