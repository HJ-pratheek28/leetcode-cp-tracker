# LeetCode & Competitive Programming Tracker

> **A pattern-first problem-solving system — not a solved-count leaderboard.**

A structured workspace for building algorithmic intuition, recording why an approach works, revisiting mistakes with spaced repetition, and progressing from foundational patterns to advanced data structures and algorithms.

**Primary language:** C++ · **Also welcome:** Python  
**Focus:** pattern recognition · correctness proofs · complexity analysis · deliberate practice

---

## Operating principles

- **Reason before code.** Identify constraints, brute force, bottleneck, and the property that removes it.
- **Track understanding, not submissions.** A green verdict is not the same as independent recall.
- **Record the invariant.** Explain what remains true and why each step is safe.
- **Revisit failures.** Mistakes are reusable data; write down the exact failure mode.
- **Measure retention.** Re-solve without notes after 1, 7, and 30 days.

## Repository map

| Path | Purpose |
|---|---|
| [`problems/`](problems/) | Pattern-indexed problem log |
| [Pattern recognition guide](docs/pattern-recognition.md) | Turn problem clues into candidate approaches |
| [Algorithm roadmap](docs/algorithm-roadmap.md) | Progress from fundamentals to advanced topics |
| [Complexity reference](docs/complexity-cheatsheet.md) | Time/space costs and common data structures |
| [Solution review rubric](docs/solution-review.md) | Check correctness, proof, edge cases, and trade-offs |
| [Problem note template](templates/problem-note.md) | Consistent post-solve analysis |
| [Weekly review](templates/weekly-review.md) | Review retention and plan the next cycle |
| [Contributing guide](CONTRIBUTING.md) | Rules for maintaining the tracker |

## Pattern index

| Pattern | Tracker |
|---|---|
| Arrays & hashing | [arrays-hashing](problems/arrays-hashing.md) |
| Two pointers | [two-pointers](problems/two-pointers.md) |
| Sliding window | [sliding-window](problems/sliding-window.md) |
| Binary search | [binary-search](problems/binary-search.md) |
| Sorting & selection | [sorting-selection](problems/sorting-selection.md) |
| Stack & queue | [stack-queue](problems/stack-queue.md) |
| Linked lists | [linked-lists](problems/linked-lists.md) |
| Trees | [trees](problems/trees.md) |
| Graphs | [graphs](problems/graphs.md) |
| Dynamic programming | [dynamic-programming](problems/dynamic-programming.md) |
| Greedy | [greedy](problems/greedy.md) |
| Backtracking | [backtracking](problems/backtracking.md) |
| Bit manipulation | [bit-manipulation](problems/bit-manipulation.md) |
| Math | [math](problems/math.md) |
| Strings | [strings](problems/strings.md) |
| Mixed / advanced patterns | [other](problems/other.md) |

## Problem lifecycle

```text
Understand constraints
        ↓
Build brute force → identify bottleneck
        ↓
Find useful property / invariant
        ↓
Choose data structure or algorithm
        ↓
Prove correctness → analyze complexity
        ↓
Implement → test edge cases
        ↓
Record insight + failure mode
        ↓
Re-solve at +1 day, +7 days, +30 days
```

## Status system

| Status | Meaning |
|---|---|
| ⬜ Not started | Not attempted |
| 🟡 Attempted | Needed major hints or cannot yet explain the solution |
| ✅ Independent | Derived and implemented without solution-level help |
| 🔁 Re-solved | Independently recalled and solved during a later review |
| ⭐ Mastered | Re-solved later, can explain correctness and complexity, and can recognize when the pattern applies |

Use **⭐ Mastered** sparingly. Do not promote a problem just because the code passed once.

## Problem log format

Each pattern file uses this format:

`Problem · Difficulty · Status · Trigger / key insight · Complexity · Review dates`

For a new entry, copy the [problem note template](templates/problem-note.md) for detailed analysis and keep the tracker row concise. Link to the original problem statement; keep long explanations and personal notes in Markdown rather than bloating the index.

## Weekly operating loop

- [ ] Re-solve 🟡 problems without looking at saved notes.
- [ ] Revisit due +1 / +7 / +30 day reviews.
- [ ] Explain one algorithm's invariant and correctness out loud.
- [ ] Solve one new problem and write the brute-force baseline first.
- [ ] Record a failed approach and what disproved it.
- [ ] Update [the weekly review](templates/weekly-review.md).
- [ ] Choose next week's focus based on recurring mistakes, not random difficulty.

## Definition of a strong solution

- Correct for edge cases and constraints
- Clear invariant or state definition
- Correctness argument, not intuition alone
- Time and auxiliary-space complexity
- No unnecessary complexity or premature optimization
- Can be reconstructed without copying the saved code

## Start here

1. Pick one topic from the [algorithm roadmap](docs/algorithm-roadmap.md).
2. Attempt a problem before reading editorials.
3. Use the [pattern recognition guide](docs/pattern-recognition.md) when stuck.
4. Fill out the [problem note template](templates/problem-note.md).
5. Re-solve it on schedule and only then upgrade its status.

---

*Built for long-term algorithmic skill: fewer blind submissions, more repeatable reasoning.*
