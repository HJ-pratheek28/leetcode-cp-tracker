# Complexity Cheatsheet

Costs depend on implementation and assumptions. Always analyze the operations your algorithm actually performs.

## Common time costs

| Complexity | Example |
|---|---|
| O(1) | Array index access; average hash lookup |
| O(log n) | Binary search; balanced BST operation |
| O(n) | One traversal; prefix-sum build |
| O(n log n) | Comparison sort; repeated heap operations |
| O(n²) | All pairs; basic 2D DP |
| O(n³) | Three nested loops; Floyd–Warshall |
| O(2ⁿ) | Enumerating subsets |
| O(n!) | Enumerating permutations |

## Data structure trade-offs

| Structure | Typical cost | Caveat |
|---|---|---|
| Vector | Index O(1), search O(n), append amortized O(1) | Reallocation may invalidate references |
| Sorted array | Binary search O(log n) | Insert/delete O(n) |
| Hash map/set | Average lookup and update O(1) | Worst case differs; not sorted |
| `std::map` / balanced BST | Lookup/update O(log n) | Sorted keys, higher constants |
| Stack / queue | Supported-end operations O(1) | Restricted access |
| Binary heap | Peek O(1), push/pop O(log n) | Arbitrary search O(n) |
| Linked list | Search O(n); known-node insertion/deletion O(1) | Finding position costs O(n); poor locality |
| DSU | Near O(1) amortized find/union | Standard DSU does not support arbitrary deletions |
| Fenwick tree | Prefix query/update O(log n) | Suits cumulative operations |
| Segment tree | Range query/point update O(log n) | Flexible, more implementation overhead |
| Trie | O(L) for key length L | Memory usage can be high |

## Graph algorithms

Let V be vertices and E edges.

| Algorithm | Typical cost | Conditions |
|---|---|---|
| BFS / DFS | O(V + E) | Adjacency list |
| Topological sort | O(V + E) | Directed acyclic graph |
| Dijkstra with binary heap | O((V + E) log V) | Non-negative edge weights |
| Bellman–Ford | O(VE) | Negative edges; detects reachable negative cycles |
| Kruskal | O(E log E) | Minimum spanning tree, DSU |
| Prim with binary heap | O(E log V) | Minimum spanning tree |
| Floyd–Warshall | O(V³) time, O(V²) space | All-pairs shortest paths on smaller graphs |

## Space terminology
- **Input space:** the provided input.
- **Auxiliary space:** extra working memory.
- **Output space:** memory for the answer.
- **Call stack:** recursion can require O(n) or O(V).

State the convention used when comparing solutions.

## C++ pitfalls
- Check integer ranges; use `long long` when constraints require it.
- Deep recursive DFS can overflow the call stack; consider iterative traversal.
- Average hash lookup is not guaranteed worst-case O(1).
- Vector append is amortized O(1), though one reallocation can cost O(n).
- Adjacency matrices use O(V²) memory; adjacency lists use O(V + E).
