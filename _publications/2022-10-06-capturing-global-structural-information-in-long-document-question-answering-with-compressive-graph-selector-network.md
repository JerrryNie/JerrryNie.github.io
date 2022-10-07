---
title: "Capturing Global Structural Information in Long Document Question Answering with Compressive Graph Selector Network"
collection: publications
permalink: /publication/2022-10-06-capturing-global-structural-information-in-long-document-question-answering-with-compressive-graph-selector-network
excerpt: 'In this study, we propose **C**ompressive **G**raph **S**elector **N**etwork (CGSN) to capture the global structure in a compressive and iterative manner. Specifically, the proposed model consists of three modules: local graph network, global graph network and evidence memory network. Firstly, the local graph network builds the graph structure of the chunked segment in token, sentence, paragraph and segment levels to capture the short-term dependency of the text. Secondly, the global graph network selectively receives the information of each level from the local graph, compresses them into the global graph nodes and applies graph attention into the global graph nodes to build the long-range reasoning over the entire text in an iterative way. Thirdly, the evidence memory network is designed to alleviate the redundancy problem in the evidence selection via saving the selected result in the previous steps. Extensive experiments show that the proposed model outperforms previous methods on two datasets.'
date: 2022-10-06
venue: 'EMNLP 2022'
paperurl: 'https://arxiv.org/abs/xxxx.xxxxx'
citation: 'Nie, Y., Huang, H., Wei, W., & Mao, X. L. (2022). Capturing Global Structural Information in Long Document Question Answering with Compressive Graph Selector Network. arXiv preprint arXiv:2210.xxxxx.'
---

## Abstract
Long document question answering is a challenging task due to its demands for complex reasoning over long text. Previous works usually take long documents as non-structured flat texts or only consider the local structure in long documents. However, these methods usually ignore the global structure of the long document, which is essential for long-range understanding. To tackle this problem, we propose \textbf{C}ompressive \textbf{G}raph \textbf{S}elector \textbf{N}etwork (CGSN) to capture the global structure in a compressive and iterative manner. Specifically, the proposed model consists of three modules: local graph network, global graph network and evidence memory network. Firstly, the local graph network builds the graph structure of the chunked segment in token, sentence, paragraph and segment levels to capture the short-term dependency of the text. Secondly, the global graph network selectively receives the information of each level from the local graph, compresses them into the global graph nodes and applies graph attention into the global graph nodes to build the long-range reasoning over the entire text in an iterative way. Thirdly, the evidence memory network is designed to alleviate the redundancy problem in the evidence selection via saving the selected result in the previous steps. Extensive experiments show that the proposed model outperforms previous methods on two datasets.

[Download paper here](https://arxiv.org/pdf/2210.xxxxx.pdf)

Recommended citation: Nie, Y., Huang, H., Wei, W., & Mao, X. L. (2022). Capturing Global Structural Information in Long Document Question Answering with Compressive Graph Selector Network. arXiv preprint arXiv:2210.xxxxx.
