# Mistakes Log

## View log: 

1. 25/10/2026

## Mistake list:

- [x] https://usaco.org/index.php?page=viewproblem2&cpid=691 :
- [P P H P S]
- (Here one kind is max before this, and one kind is max after is, these two kinds could have been same)

- [ ] https://atcoder.jp/contests/abc125/tasks/abc125_c :
- The element that we need to remove is the element whose neighbours have highest cumulative gcd from their end. The highest gcd would be their neighbour's gcd.

- [ ] https://codeforces.com/contest/1398/problem/C:
- Didn't realise the condition can be simplified using maths.
- Didn't realise multplying two numbers can lead to int overflow

- [ ] https://cses.fi/problemset/task/1662:
- Instead of using a nested loop, we can use frequency map (didn't realise that)
- Didn't account for % operator behaving differently for negative numbers.

- [ ] https://cses.fi/problemset/task/1661:
- Should have used map to find the sub array with size x.
- for that should have learnt the standard algorithm (make a map that keeps track of previous prefix_sum and add the arrays)
- didn't realise unordered_map goes from O(N) -> O(N^2) for bigger N, shoudl have used map instead O(Nlog(N))

- [ ] https://usaco.org/index.php?page=viewproblem2&cpid=738:
- didn't realise a vector containing 10^9 int will take 3.7GB of RAM.