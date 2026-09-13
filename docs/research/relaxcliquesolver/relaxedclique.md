---
title: Relaxed Cliques
description: Algorithms and software for finding and enumerating relaxed cliques, including k-plexes, k-defective cliques, and s-bundles.
lang: en
---

# Relaxed Cliques

A clique requires every pair of vertices to be adjacent. Relaxed-clique models allow limited departures from this condition, providing ways to study cohesive structures in graphs.

Our work examines both finding a largest structure and enumerating maximal structures, with attention to algorithmic guarantees and practical performance on large graphs.

## ListPlex: enumerating maximal k-plexes

A *k*-plex allows each vertex to have a limited number of non-neighbors within the selected set. ListPlex addresses the enumeration of maximal *k*-plexes in large real-world graphs.

**Zhengren Wang, Yi Zhou, Mingyu Xiao, Bakhadyr Khoussainov.** Listing Maximal k-Plexes in Large Real-World Graphs. *The Web Conference*, 2022.

[Paper](https://arxiv.org/abs/2202.08737){ .md-button }
[Code](https://github.com/joey001/ListPlex){ .md-button }

## Maximum k-defective clique

A *k*-defective clique permits at most *k* missing edges in the selected vertex set. We study methods for finding maximum such structures in massive graphs.

**Xiaoyu Chen, Yi Zhou, Jin-Kao Hao.** Computing maximum k-defective cliques in massive graphs. *Computers & Operations Research* 127, 2021.

[Paper](https://www.sciencedirect.com/science/article/pii/S0305054820302483){ .md-button }
[Code](https://github.com/chenxiaoyu233/k-defective){ .md-button }

Related work: **Chunyu Luo, Yi Zhou, Zhengren Wang, Mingyu Xiao.** A Faster Branching Algorithm for the Maximum k-Defective Clique Problem. *ECAI*, 2024.

## Maximum s-bundle

We also develop branch-and-bound methods for the maximum *s*-bundle problem, another model of cohesive graph structures.

**Yi Zhou, Weibo Lin, Jin-Kao Hao, Mingyu Xiao, Yan Jin.** An effective branch-and-bound algorithm for the maximum s-bundle problem. *European Journal of Operational Research*, 2021.

[Paper](https://www.sciencedirect.com/science/article/pii/S0377221721003957){ .md-button }
[Code](https://github.com/joey001/max-s-bundle){ .md-button }

## Explore further

See the [publications page](../publication.md) for related work. Each software repository provides its own usage information.

Interested in graph algorithms? Read our [guidance for prospective students (Chinese)](../../aegroup/aegroup_zh.md#_8).
