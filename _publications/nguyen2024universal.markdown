---
layout: publication
title: 'Uniadapt: A Universal Adapter For Knowledge Calibration'
authors: Tai D. Nguyen, Long H. Pham, Jun Sun
conference: "Arxiv"
year: 2024
bibkey: nguyen2024universal
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.00454'}
tags: ['RAG', 'Model Architecture']
---
Large Language Models (LLMs) require frequent updates to correct errors and
keep pace with continuously evolving knowledge in a timely and effective
manner. Recent research in it model editing has highlighted the challenges in
balancing generalization and locality, especially in the context of lifelong
model editing. We discover that inserting knowledge directly into the model
often causes conflicts and potentially disrupts other unrelated pre-trained
knowledge. To address this problem, we introduce UniAdapt, a universal adapter
for knowledge calibration. Inspired by the Mixture of Experts architecture and
Retrieval-Augmented Generation, UniAdapt is designed with a vector-assisted
router that is responsible for routing inputs to appropriate experts. The
router maintains a vector store, including multiple shards, to construct
routing vectors based on semantic similarity search results. UniAdapt is fully
model-agnostic and designed for seamless plug-and-play integration.
Experimental results show that UniAdapt outperforms existing lifelong model
editors and achieves exceptional results in most metrics.
