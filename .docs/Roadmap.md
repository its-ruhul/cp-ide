# Codeforces Roadmap: 1000 to 1600+

Oct 21, 2026 · @Esummit

## Where you are and the real wall

At 1000, the wall is almost never advanced data structures; it is observation, math and a few core techniques. Segment trees, Fenwick trees and DSU start mattering around 1600+.

- **Current profile:** 917 rating (Newbie), 191 problems solved, 64-day max streak, but only 9 problems last month. The first fix is volume, not theory.
- **What blocks 1000–1400 problems:** greedy and observation, math basics (parity, divisibility, GCD, primes, modular arithmetic), binary search on the answer, and prefix sums with two pointers.
- **The trap:** jumping to advanced DS now teaches a lot but does not move your rating. The phases below follow when each topic starts showing up in contests.

## Phase 1: 1000 → 1200 (about 4–6 weeks)

Goal: make the standard 1100–1300 tricks automatic.

**Topics**

- [ ] Sorting plus greedy, with exchange-argument thinking (why is this choice optimal?)
- [ ] Prefix sums, difference arrays, frequency counting with maps and sets
- [ ] Two pointers and sliding window
- [ ] Number theory basics: Sieve of Eratosthenes, GCD/LCM, divisors in O(√n), modular arithmetic, fast exponentiation
- [ ] Bit manipulation: XOR properties, checking and setting bits, subset enumeration
- [ ] STL fluency: set, map, multiset, priority\_queue, lower\_bound

**Practice**

- Solve problems rated 1100–1300, about 4–5 a day.
- Upsolve all Div. 2 A/B and Div. 3 A–D problems from contests you take.

## Phase 2: 1200 → 1400 (about 6–8 weeks)

Goal: add the first real algorithmic tools, especially binary search and DP.

**Topics**

- [ ] Binary search on the answer (very high yield at this level)
- [ ] Constructive problems: building arrays and permutations that satisfy given conditions
- [ ] Recursion and backtracking
- [ ] Intro DP: 1D/2D DP, knapsack, LIS, grid paths — learn to define states, not memorize patterns
- [ ] Graph basics: adjacency lists, BFS, DFS, connected components, grid BFS
- [ ] Combinatorics basics: nCr mod p with precomputed factorials

**Practice**

- Solve problems rated 1300–1500.
- Take every Div. 3 and Educational round live.

## Phase 3: 1400 → 1600 (about 2–3 months)

This is where real data structures and algorithms enter.

- [ ] Graphs: Dijkstra, topological sort, cycle detection, bipartite check
- [ ] Trees: DFS on trees, subtree sizes, tree diameter
- [ ] DSU with path compression and union by size
- [ ] DP: bitmask DP, DP on trees, DP with prefix-sum optimisation
- [ ] Fenwick tree (BIT): point updates, range sums, counting inversions
- [ ] Strings: hashing basics, prefix-function / KMP

## Phase 4: 1600+ (when you get there)

- [ ] Segment trees, including lazy propagation
- [ ] LCA with binary lifting, and sparse tables
- [ ] MST (Kruskal/Prim); shortest paths with 0-1 BFS and Floyd–Warshall
- [ ] Digit DP, interval DP, Z-function and hashing problems

## How to learn a new concept

This four-step loop closes the theory gap while using your implementation strength.

1. **Read** the CP-Algorithms article or the matching chapter of the Competitive Programmer's Handbook (Antti Laaksonen, free PDF).
2. **Implement it from scratch** without looking.
3. **Solve 5–10 problems** tagged with that topic, starting easy. CSES and the USACO Guide have clean practice sets.
4. **Mix it in:** go back to unfiltered practice, because contests never tell you the tag.

## Practice rules

These habits matter more than which topic you study.

- **Rating band:** practice at your rating +200 to +300. Problems you can already solve build speed, not skill.
- **Struggle window:** give each problem 30–45 minutes, then read the editorial. Re-solve it without notes the next day.
- **Upsolve every contest:** solve at least one problem past where you got stuck.
- **Mistakes log:** one line per failed problem with the key idea you missed. Reread it weekly; this is the best way to build observation skill.
- **Contests:** two or more rated contests a week. Don't fear rating drops at this stage.
- **Volume target:** about 100 problems a month.

## Resources and timeline

A realistic target is about 1400 (Specialist) in 4–5 months and about 1600 in 8–10 months, if you keep up the volume.

| Resource | Use it for |
| --- | --- |
| [CSES Problem Set](https://cses.fi/problemset/) | Best practice set for core techniques |
| [USACO Guide](https://usaco.guide/) | Structured Bronze → Gold path, roughly 1000 → 1700 |
| [Codeforces EDU](https://codeforces.com/edu/courses) | Courses with problems on binary search, two pointers, segment trees, DSU |
| [CP-Algorithms](https://cp-algorithms.com/) | Theory reference for each topic |
| [Competitive Programmer's Handbook](https://cses.fi/book/book.pdf) | Free book covering most of Phases 1–3 |
| YouTube: Errichto, Colin Galen | Thinking process and how to practice |

**Sources:** [MajorRay – Codeforces profile](https://codeforces.com/profile/MajorRay)
