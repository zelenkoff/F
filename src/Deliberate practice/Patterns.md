### Constant-time slice

**Where could be useful**:

1. Multiple patterns search in a string (E.g. find duplicates). All such problems usually could be solved by sliding window approach in a linear time. The challenge here is how to implement constant-time slice to fit into this linear time.

**Implementations**:

1. Bitmasks – constant-time slice using bitmasks;
2. Rabin-Karp – constant-time slice using rolling hash algorithm;

Last two approaches have `O(N−L)` (N is string.length and L is substring.length) time complexity and moderate space consumption even in the case of large sequences.

**Tasks to practice**:**

1. [Repeated DNA sequences](https://leetcode.com/problems/repeated-dna-sequences/);
2. [Find all anagrams in a string](https://leetcode.com/problems/find-all-anagrams-in-a-string/);
3. [Longest Duplicate Substring](https://leetcode.com/problems/longest-duplicate-substring/);
