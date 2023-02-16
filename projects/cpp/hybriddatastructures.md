# hybrid-data-structures

[![](https://img.shields.io/badge/project-link-blue)](https://github.com/luo-anthony/hybrid-data-structures)

## Description

I plan to make `hybrid-data-structures`, a C++ library that include one (or more) performance/cache optimized hybrid data structures (as a stretch goal, it would be cool if these data structures could also optimize for the access pattern). One possible hybrid data structure:

- Hybrid HashSet or HashMap that uses a dense array for lookups for small capacities, hash-based data structures for medium-large capacities, and tries / various trees for extremely large capacities (to avoid hash collision overhead). To optimize for access pattern, the underlying data structure could utilize a trie or splay tree, or exploit different types of probing (random, linear, quadratic, etc.) / seperate chaining depending on the access pattern (this optimizes for cache locality).

This project is inspired by [LLVM's high-performance hybrid data structures](https://www.youtube.com/watch?v=vElZc6zSIXM&list=PLiDK46vnsTT-JerJ8k5-W5L-yKvSu0M41&index=3).
