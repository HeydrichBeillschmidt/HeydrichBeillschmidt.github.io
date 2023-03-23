---
title: "uGrapher: High-performance Graph Operator Computation via Unified Abstraction for Graph Neural Networks"
collection: publications
permalink: /publication/uGrapher
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2022-07-01
venue: 'The 28th Conference on Architectural Support for Programming Languages and Operating Systems (ASPLOS'23)'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
As graph neural networks (GNNs) have achieved great success in many graph learning problems, it is of paramount im- portance to support their efficient execution. Different graphs and different operators present different patterns during execution. However, there is still a gap in the existing GNN acceleration research to explore adaptive parallelism. We show that existing GNN frameworks rely handwritten static kernels, which are fail to achieve the best performance across different graph operators and input graph structures. In this work, we propose μGrapher, a unified interface that achieves near-optimal performance for different graph operators and datasets. The existing GNN frameworks can easily integrate our design for its simple and unified API. We take a principled approach that decouples a graph operator’s computation and schedule to achieve that. We first build a GNN-specific opera- tor abstraction that incorporates the semantics of graph ten- sors and graph loops. We explore various schedule strategies based on the abstraction that can balance the well-established trade-off relationship between parallelism, locality, and effi- ciency. Our evaluation shows that μ Gra pher can bring up to 29.1× (4× on average) performance improvement over the state-of-the-art baselines on two studied NVIDIA GPUs.

<!-- [Download paper here](http://academicpages.github.io/files/paper1.pdf) -->

<!-- Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1). -->