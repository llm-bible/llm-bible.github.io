---
layout: publication
title: 'Cool-fusion: Fuse Large Language Models Without Training'
authors: Liu Cong, Quan Xiaojun, Pan Yan, Lin Liang, Wu Weigang, Chen Xu
conference: "Arxiv"
year: 2024
bibkey: liu2024cool
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.19807"}
tags: ['Applications', 'Efficiency And Optimization', 'Language Modeling', 'Merging', 'RAG', 'Training Techniques']
---
We focus on the problem of fusing two or more heterogeneous large language
models (LLMs) to facilitate their complementary strengths. One of the
challenges on model fusion is high computational load, i.e. to fine-tune or to
align vocabularies via combinatorial optimization. To this end, we propose
*Cool-Fusion*, a simple yet effective approach that fuses the knowledge of
heterogeneous source LLMs to leverage their complementary strengths.
*Cool-Fusion* is the first method that does not require any type of
training like the ensemble approaches. But unlike ensemble methods, it is
applicable to any set of source LLMs that have different vocabularies. The
basic idea is to have each source LLM individually generate tokens until the
tokens can be decoded into a text segment that ends at word boundaries common
to all source LLMs. Then, the source LLMs jointly rerank the generated text
segment and select the best one, which is the fused text generation in one
step. Extensive experiments are conducted across a variety of benchmark
datasets. On *GSM8K*, *Cool-Fusion* increases accuracy from three
strong source LLMs by a significant 8%-17.8%.
