# Pattern Recognition: From Clues to Algorithms

Treat clues as hypotheses, not a keyword-to-algorithm dictionary. Verify each candidate against constraints and correctness.

## Decision process
1. Restate the exact task and output.
2. Read constraints and estimate the maximum feasible complexity.
3. Build a brute-force baseline.
4. Identify repeated work: scans, subproblems, candidate enumeration, or graph exploration.
5. Look for structure: ordering, monotonicity, bounded values, overlapping subproblems, connectivity, or a provable local-choice property.
6. State the invariant or DP state before coding.
7. Test boundary cases and adversarial inputs.
8. Prove correctness and analyze time plus auxiliary space.

## Clue → candidate → verify

| Clue | Candidate | Verification |
|---|---|---|
| Frequent membership / counts | Hash set or map | Expected-time behavior acceptable? |
| Sorted pair condition | Two pointers / binary search | Can ordering safely discard candidates? |
| Contiguous subarray / substring | Sliding window / prefix sums | Negative values may invalidate standard window logic. |
| Monotonic search predicate | Binary search on answer | Prove predicate is monotonic. |
| Range queries | Prefix sums / Fenwick / segment tree | Are updates required? |
| Next greater / smaller | Monotonic stack | State exactly why an item is popped. |
| Level distance / unweighted shortest path | BFS | Are edge weights equal? |
| Connectivity / components | DFS, BFS, DSU | Are edges static or dynamic? |
| Prerequisite ordering | Topological sort | Is the graph a DAG? |
| Weighted shortest path | Dijkstra / Bellman–Ford | Are weights non-negative? Can negative cycles exist? |
| All valid combinations | Backtracking | Define choice, state, pruning, and undo. |
| Overlapping optimal subproblems | Dynamic programming | State, recurrence, base case, evaluation order. |
| Local choice seems optimal | Greedy | Prove by exchange argument or invariant. |
| Kth / top K | Heap, quickselect, counting | Are worst-case guarantees or mutation relevant? |
| String prefixes / matching | Trie, KMP, Z-function, rolling hash | Prefix queries or exact matching? |
| Many tree queries | LCA, binary lifting, Euler tour | What are query types and constraints? |
| Small N with subset choices | Bitmask DP / meet-in-the-middle | Is exponential complexity feasible? |

## Rough constraint filter

| n | Common target to investigate |
|---:|---|
| ≤ 20 | O(2ⁿ), sometimes O(n·2ⁿ) |
| ≤ 100 | O(n³) may fit |
| ≤ 1,000 | O(n²) may fit |
| ≤ 100,000 | O(n log n) or O(n) is common |
| ≥ 1,000,000 | Usually linear or near-linear |

These are heuristics, not guarantees. Constants, test cases, and runtime limits matter.

## When stuck: 10-minute protocol
- **0–2 min:** constraints, examples, brute force.
- **2–5 min:** identify repeated work and useful structure.
- **5–8 min:** propose an optimization and justify why it is safe.
- **8–10 min:** test edge cases and estimate complexity.

If still stuck, take a small hint, close the editorial, and reconstruct the reasoning. Record the hint level honestly.

## After every solve
- What clue made the pattern plausible?
- Why is brute force too slow?
- What invariant/state makes the method correct?
- Which edge case breaks a careless implementation?
- What variation would change the algorithm?
