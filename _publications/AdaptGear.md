---
title: "AdaptGear: Accelerating GNN Training via Adaptive Subgraph-Level Kernels on GPUs"
collection: publications
permalink: /publication/AdaptGear
# excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
# date: 2010-10-01
venue: 'The 20th ACM International Conference on Computing Frontiers (CF ’23)'
# paperurl: 'http://academicpages.github.io/files/paper2.pdf'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
Graph neural networks (GNNs) are powerful tools for exploring and learning from graph structures and features. As such, achieving high-performance execution for GNNs becomes crucially important. Prior works have proposed to explore the sparsity (i.e., low density) in the input graph to accelerate GNNs, which uses the full-graph-level or block-level sparsity format. We show that they fail to balance the sparsity benefit and kernel execution efficiency. In this paper, we propose a novel system, referred to as AdaptGear, that addresses the challenge of optimizing GNN performance by leveraging kernels tailored to the density characteristics at the subgraph level. Meanwhile, we also propose a method that dynamically chooses the optimal set of kernels for a given input graph. Our evaluation shows that AdaptGear can achieve a significant performance improvement, up to 6.49 \times6.49× (1.87 \times1.87× on average), over the state-of-the-art works on two mainstream NVIDIA GPUs across various datasets.

<!-- [Download paper here](http://academicpages.github.io/files/paper2.pdf) -->

<!-- Recommended citation: Your Name, You. (2010). "Paper Title Number 2." <i>Journal 1</i>. 1(2). -->