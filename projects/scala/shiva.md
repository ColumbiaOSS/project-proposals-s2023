# [shiva](https://github.com/saucam/shiva): Simple High dimensional Indexed Vector search Algorithms

[![CI](https://github.com/saucam/shiva/actions/workflows/ci.yaml/badge.svg?branch=main)](https://github.com/saucam/shiva/actions/workflows/ci.yaml)
[![](https://img.shields.io/github/license/saucam/shiva)](https://github.com/saucam/shiva/blob/main/LICENSE.md)
[![Sonatype Releases](https://img.shields.io/nexus/r/io.github.saucam/shiva-core_2.13?nexusVersion=2&server=https%3A%2F%2Fs01.oss.sonatype.org)](https://s01.oss.sonatype.org/content/repositories/releases/io/github/saucam/shiva-core_2.13/)
[![Docs](https://img.shields.io/badge/Docs-Website-yellow)](https://saucam.github.io/shiva)

Recently, I got interested in indexing libraries for similarity search. These are highly efficient libraries that index vector data and can be used to query 'similar' vector based on metrics like euclidean distance etc.

Some of the very popular implementations are:

- [Faiss](https://github.com/facebookresearch/faiss)
- [hnswlib](https://github.com/nmslib/hnswlib)

Most of these libraries have C++ implementations with python bindings, but there is general [interest in the community for JVM implementations](https://github.com/facebookresearch/faiss/issues/105) as well.

I was able to find a java implementation of [hnswlib here](https://github.com/jelmerk/hnswlib).
The major limitations of such libraries is memory. They rely on storing all the indexed data in-memory. So they need to be very memory efficient. On the other hand, they need to be really fast to handle queries in reasonable time.

I have been working professionally with scala for 6+ years (out of 13+ years) as a developer.
I would like to roll my own scala implementation. Here is what I would do differently:

- Concentrate on a simple application level use-case of finding similar items, and do away with other constraints and additional features that these implementations support. In particular, the java implementation above guarantees thread safety and therefore has to use atomic references bringing in additional overhead while storing the objects in memory.
- Simple applications would not require thread safety of index structures and if they would, they could handle it on the application layer itself.
- Take a hit (within reason) on performance to optimize memory.
- I want to experiment with and use faster primitive data libraries like [hppc](https://labs.carrotsearch.com/hppc.html), [fastutil](https://fastutil.di.unimi.it/), [koloboke](https://github.com/leventov/Koloboke) etc for storing the vectors.
- Experiment with storing data off-heap, to further reduce memory requirements.
- Eventually I would like to support many different indexes since each has their own pros and cons.
- Experiment with possibilty to use data structures that spill to disk? There is a newer [alternate hybrid algorithm](https://openreview.net/forum?id=-1rrzmJCp4) that claims to support data both in disk and in memory but its performance with different kinds of data sets is yet to be proven.
