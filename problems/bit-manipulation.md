# Bit Manipulation

**Recognition clues:** binary representation, parity, subsets, XOR cancellation, masks, powers of two.

| Problem | Difficulty | Status | Key idea / mistake | Review +1d | Review +7d | Review +30d |
|---|---|---|---|---|---|---|
| [Single Number](https://leetcode.com/problems/single-number/) | Easy | ⬜ | XOR cancels equal pairs | | | |
| [Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/) | Easy | ⬜ | n &= n-1 removes lowest set bit | | | |
| [Counting Bits](https://leetcode.com/problems/counting-bits/) | Easy | ⬜ | dp[i] = dp[i >> 1] + (i & 1) | | | |
| [Reverse Bits](https://leetcode.com/problems/reverse-bits/) | Easy | ⬜ | Shift result and append lowest input bit | | | |
| [Missing Number](https://leetcode.com/problems/missing-number/) | Easy | ⬜ | XOR indices and values, or use sum | | | |
