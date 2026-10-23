# Complete LeetCode + Competitive Programming Curriculum

> Follow this in order. This is a skill-building sequence, not a race to collect submissions. C++ is the primary contest language; Python is useful for quick experiments and selected interview practice.

## How to use this curriculum

For each problem:
1. Spend 20–40 minutes attempting it (more for a stretch problem).
2. Write the brute-force idea and complexity first.
3. If stuck, take a small hint before reading a full solution.
4. Implement from a blank file, test edge cases, and explain correctness.
5. Mark **Independent** only if you derived it without solution-level help.
6. Re-solve after 1, 7, and 30 days.

**Statuses:** ⬜ Not started · 🟡 Attempted / needed help · ✅ Independent · 🔁 Re-solved later · ⭐ Mastered and transferable.

## Stage 0 — Setup and complexity (3–5 days)

- [ ] Set up a C++17/20 template, fast I/O, compiler, debugger, and local test workflow.
- [ ] Learn Big-O, auxiliary space, amortized complexity, integer ranges, references, iterators, and STL containers.
- [ ] Practice input/output, loops, functions, sorting, custom comparators, pairs, vectors, strings, maps, sets, stacks, queues, heaps.
- [ ] Implement linear search, binary search, insertion sort, merge sort, gcd, sieve, prefix sums, and frequency counting from scratch.

**Gate:** Explain why O(n log n) beats O(n²) at scale; debug a wrong answer without changing code randomly.

## Stage 1 — Arrays, hashing, strings, basic implementation

Solve in this order:
1. [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/)
2. [Two Sum](https://leetcode.com/problems/two-sum/)
3. [Valid Anagram](https://leetcode.com/problems/valid-anagram/)
4. [Majority Element](https://leetcode.com/problems/majority-element/)
5. [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)
6. [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)
7. [Move Zeroes](https://leetcode.com/problems/move-zeroes/)
8. [Missing Number](https://leetcode.com/problems/missing-number/)
9. [Single Number](https://leetcode.com/problems/single-number/)
10. [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/)
11. [Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/)
12. [Ransom Note](https://leetcode.com/problems/ransom-note/)
13. [Group Anagrams](https://leetcode.com/problems/group-anagrams/)
14. [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)
15. [Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/)
16. [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/)
17. [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/)
18. [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)

**Patterns:** counting, hash maps/sets, in-place modification, prefix/suffix, frequency maps, prefix-sum + frequency.

**Gate:** solve a fresh Easy in 20 minutes and a familiar Medium in 35 minutes; explain expected vs worst-case hash complexity.

## Stage 2 — Two pointers, sliding window, prefix sums

19. [Valid Palindrome](https://leetcode.com/problems/valid-palindrome/) — re-solve with two pointers.
20. [Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)
21. [3Sum](https://leetcode.com/problems/3sum/)
22. [Container With Most Water](https://leetcode.com/problems/container-with-most-water/)
23. [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/)
24. [Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/)
25. [Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/)
26. [Permutation in String](https://leetcode.com/problems/permutation-in-string/)
27. [Find All Anagrams in a String](https://leetcode.com/problems/find-all-anagrams-in-a-string/)
28. [Maximum Average Subarray I](https://leetcode.com/problems/maximum-average-subarray-i/)
29. [Range Sum Query - Immutable](https://leetcode.com/problems/range-sum-query-immutable/)
30. [Continuous Subarray Sum](https://leetcode.com/problems/continuous-subarray-sum/)

**Critical distinction:** the classic moving window relies on a property that lets the boundary move safely; negative numbers often invalidate the usual sum-window argument.

**Gate:** given an unfamiliar contiguous-range problem, decide between sliding window, prefix sums, and prefix-sum hashing and justify the choice.

## Stage 3 — Sorting, intervals, binary search, selection

31. [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/)
32. [Sort Colors](https://leetcode.com/problems/sort-colors/)
33. [Largest Number](https://leetcode.com/problems/largest-number/)
34. [Merge Intervals](https://leetcode.com/problems/merge-intervals/)
35. [Insert Interval](https://leetcode.com/problems/insert-interval/)
36. [Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/)
37. [Binary Search](https://leetcode.com/problems/binary-search/)
38. [Search Insert Position](https://leetcode.com/problems/search-insert-position/)
39. [Find First and Last Position of Element in Sorted Array](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)
40. [Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/)
41. [Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)
42. [Koko Eating Bananas](https://leetcode.com/problems/koko-eating-bananas/)
43. [Capacity To Ship Packages Within D Days](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/)
44. [Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/) — stretch
45. [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) — compare heap, quickselect, and sorting.

**Gate:** write lower_bound/upper_bound correctly, prove a monotonic feasibility predicate, and maintain binary-search invariants without off-by-one bugs.

## Stage 4 — Linked lists, stacks, queues, monotonic structures

46. [Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/)
47. [Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/)
48. [Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)
49. [Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)
50. [Reorder List](https://leetcode.com/problems/reorder-list/)
51. [Add Two Numbers](https://leetcode.com/problems/add-two-numbers/)
52. [Valid Parentheses](https://leetcode.com/problems/valid-parentheses/)
53. [Min Stack](https://leetcode.com/problems/min-stack/)
54. [Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/)
55. [Daily Temperatures](https://leetcode.com/problems/daily-temperatures/)
56. [Next Greater Element I](https://leetcode.com/problems/next-greater-element-i/)
57. [Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/)
58. [Sliding Window Maximum](https://leetcode.com/problems/sliding-window-maximum/)
59. [Implement Queue using Stacks](https://leetcode.com/problems/implement-queue-using-stacks/)

**Gate:** explain the stack invariant and exactly why each element is pushed/popped a bounded number of times.

## Stage 5 — Recursion, backtracking, bit manipulation

60. [Subsets](https://leetcode.com/problems/subsets/)
61. [Subsets II](https://leetcode.com/problems/subsets-ii/)
62. [Permutations](https://leetcode.com/problems/permutations/)
63. [Combination Sum](https://leetcode.com/problems/combination-sum/)
64. [Combination Sum II](https://leetcode.com/problems/combination-sum-ii/)
65. [Generate Parentheses](https://leetcode.com/problems/generate-parentheses/)
66. [Word Search](https://leetcode.com/problems/word-search/)
67. [N-Queens](https://leetcode.com/problems/n-queens/) — stretch
68. [Counting Bits](https://leetcode.com/problems/counting-bits/)
69. [Reverse Bits](https://leetcode.com/problems/reverse-bits/)
70. [Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/)
71. [Single Number II](https://leetcode.com/problems/single-number-ii/)

For every recursive solution, define the state, choices, base case, pruning rule, and undo step.

## Stage 6 — Trees, BSTs, heaps, tries

72. [Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/)
73. [Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/)
74. [Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/)
75. [Balanced Binary Tree](https://leetcode.com/problems/balanced-binary-tree/)
76. [Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/)
77. [Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/)
78. [Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)
79. [Lowest Common Ancestor of a Binary Search Tree](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/)
80. [Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/)
81. [Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)
82. [Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/) — stretch
83. [Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/) — re-solve using a heap
84. [Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/)
85. [Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/)
86. [Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/)

**Gate:** distinguish return values from global answers in tree recursion; explain heap invariants and BST ordering bounds.

## Stage 7 — Greedy, graphs, union-find, shortest paths

87. [Jump Game](https://leetcode.com/problems/jump-game/)
88. [Jump Game II](https://leetcode.com/problems/jump-game-ii/)
89. [Gas Station](https://leetcode.com/problems/gas-station/)
90. [Hand of Straights](https://leetcode.com/problems/hand-of-straights/)
91. [Is Subsequence](https://leetcode.com/problems/is-subsequence/)
92. [Number of Islands](https://leetcode.com/problems/number-of-islands/)
93. [Max Area of Island](https://leetcode.com/problems/max-area-of-island/)
94. [Clone Graph](https://leetcode.com/problems/clone-graph/)
95. [Rotting Oranges](https://leetcode.com/problems/rotting-oranges/)
96. [Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/)
97. [Course Schedule](https://leetcode.com/problems/course-schedule/)
98. [Course Schedule II](https://leetcode.com/problems/course-schedule-ii/)
99. [Redundant Connection](https://leetcode.com/problems/redundant-connection/)
100. [Accounts Merge](https://leetcode.com/problems/accounts-merge/)
101. [Network Delay Time](https://leetcode.com/problems/network-delay-time/)
102. [Cheapest Flights Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/)
103. [Min Cost to Connect All Points](https://leetcode.com/problems/min-cost-to-connect-all-points/)
104. [Word Ladder](https://leetcode.com/problems/word-ladder/)
105. [Critical Connections in a Network](https://leetcode.com/problems/critical-connections-in-a-network/) — advanced

**Gate:** explain why BFS gives shortest paths only under suitable edge costs; explain Dijkstra's non-negative-weight condition; implement DSU with path compression and union by size/rank.

## Stage 8 — Dynamic programming, from 1D to advanced

106. [Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)
107. [Min Cost Climbing Stairs](https://leetcode.com/problems/min-cost-climbing-stairs/)
108. [House Robber](https://leetcode.com/problems/house-robber/)
109. [House Robber II](https://leetcode.com/problems/house-robber-ii/)
110. [Decode Ways](https://leetcode.com/problems/decode-ways/)
111. [Coin Change](https://leetcode.com/problems/coin-change/)
112. [Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/)
113. [Word Break](https://leetcode.com/problems/word-break/)
114. [Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/)
115. [Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/)
116. [Unique Paths](https://leetcode.com/problems/unique-paths/)
117. [Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/)
118. [Edit Distance](https://leetcode.com/problems/edit-distance/)
119. [Distinct Subsequences](https://leetcode.com/problems/distinct-subsequences/)
120. [Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/)
121. [Palindromic Substrings](https://leetcode.com/problems/palindromic-substrings/)
122. [Burst Balloons](https://leetcode.com/problems/burst-balloons/) — advanced interval DP
123. [Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/) — advanced

**Gate:** define DP state before code; explain recurrence, base cases, order of evaluation, and whether memory compression is valid.

## Stage 9 — Advanced data structures and string algorithms

- [ ] Fenwick tree / Binary Indexed Tree: point update + prefix/range sum
- [ ] Segment tree: build, point update, range query
- [ ] Lazy propagation for range updates
- [ ] Sparse table and idempotent range queries
- [ ] Coordinate compression and offline query processing
- [ ] KMP prefix function and pattern matching
- [ ] Z-function
- [ ] Rolling hash and collision caveats
- [ ] Trie variants and bitwise trie
- [ ] LCA with binary lifting and Euler tour
- [ ] Strongly connected components (Kosaraju / Tarjan)
- [ ] Bridges and articulation points
- [ ] Maximum flow / bipartite matching
- [ ] Meet-in-the-middle, digit DP, bitmask DP
- [ ] Number theory: gcd, sieve, prime factorization, modular arithmetic, fast exponentiation, modular inverse, combinations modulo prime
- [ ] DSU, Kruskal, topological DP, shortest paths review

For this stage, pair each topic with an implementation from scratch and 3–8 targeted problems. Choose problems by the exact technique; do not blindly chase Hard labels.

## Stage 10 — Competitive programming track (start in parallel after Stage 1)

LeetCode builds interview-style pattern depth; Codeforces builds speed, implementation, and adapting to unfamiliar statements. Use both.

### Codeforces rating progression

1. **800–1000:** implementation, arithmetic, strings, frequency counting, sorting, greedy basics.
2. **1000–1200:** prefix sums, two pointers, constructive algorithms, binary search basics, frequency invariants.
3. **1200–1400:** stronger greedy, binary search on answer, basic number theory, maps/sets, simple graph traversal.
4. **1400–1600:** standard graph algorithms, DP fundamentals, DSU, combinatorics, bitmasks, proof-based greedy.
5. **1600–1900:** advanced DP, shortest paths, tree techniques, segment/Fenwick trees, string algorithms, constructive reasoning.
6. **1900+:** specialized algorithms, harder proof construction, advanced data structures, geometry and flows as contest mix demands.

Ratings are guideposts, not guarantees. Solve by rating and topic; don't jump to advanced tags before fundamentals are reliable.

### Contest routine
- [ ] Start with 2–3 virtual contests or live contests per month, then increase to weekly when sustainable.
- [ ] After each contest, upsolve every problem you had a realistic path to solve.
- [ ] Write down the first failed idea and the observation that fixes it.
- [ ] Re-solve upsolved problems 3–7 days later.
- [ ] Track solve time, wrong attempts, and reason for failure—not rating alone.
- [ ] Practice implementation speed with a consistent C++ template.

## Stage 11 — Mixed practice and mastery

After completing the topic passes:
- [ ] Solve 2–4 mixed problems per week with no topic label.
- [ ] Do timed sets and virtual contests.
- [ ] Revisit weak topics from the mistake log.
- [ ] Explain one proof, invariant, or DP recurrence aloud each week.
- [ ] Re-implement core structures from memory.
- [ ] Keep a permanent list of problems that taught a reusable idea.

## Recommended weekly structure

A sustainable starting cadence:
- **3 sessions:** learn one topic and solve 2–4 targeted problems.
- **1 session:** re-solve old problems without notes.
- **1 session:** Codeforces rated practice / virtual contest.
- **1 session:** upsolve, review mistakes, and implement a data structure.
- **1 rest/light day:** no guilt-driven backlog marathons.

Increase volume only when review quality stays high. For each problem, quality of understanding matters more than the total count.

## What “mastered” means

A problem is ⭐ only when you can:
- derive the pattern from the statement and constraints;
- implement it without copied code;
- prove correctness;
- state time and auxiliary space;
- solve it again after a delay;
- explain a variation where the same approach fails or must change.

## Core resources

- [LeetCode](https://leetcode.com/problemset/)
- [Codeforces](https://codeforces.com/)
- [CSES Problem Set](https://cses.fi/problemset/)
- [USACO Guide](https://usaco.guide/)
- [CP-Algorithms](https://cp-algorithms.com/)
- [AtCoder](https://atcoder.jp/)
- [Striver A2Z DSA Sheet](https://takeuforward.org/strivers-a2z-dsa-course/strivers-a2z-dsa-course-sheet-2/)

Use one primary topic sequence at a time. Treat external sheets as supplemental practice rather than competing roadmaps.
