---
layout: publication
title: 'Date Fragments: A Hidden Bottleneck Of Tokenization For Temporal Reasoning'
authors: Gagan Bhatia, Maxime Peyrard, Wei Zhao
conference: "Arxiv"
year: 2025
bibkey: bhatia2025date
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16088'}
  - {name: "Code", url: 'https://github.com/gagan3012/date-fragments}{here'}
tags: ['Attention Mechanism', 'Has Code', 'RAG', 'Model Architecture', 'Tokenization']
---
Modern BPE tokenizers often split calendar dates into meaningless fragments, e.g., 20250312 \\(\rightarrow\\) 202, 503, 12, inflating token counts and obscuring the inherent structure needed for robust temporal reasoning. In this work, we (1) introduce a simple yet interpretable metric, termed date fragmentation ratio, that measures how faithfully a tokenizer preserves multi-digit date components; (2) release DateAugBench, a suite of 6500 examples spanning three temporal reasoning tasks: context-based date resolution, format-invariance puzzles, and date arithmetic across historical, contemporary, and future time periods; and (3) through layer-wise probing and causal attention-hop analyses, uncover an emergent date-abstraction mechanism whereby large language models stitch together the fragments of month, day, and year components for temporal reasoning. Our experiments show that excessive fragmentation correlates with accuracy drops of up to 10 points on uncommon dates like historical and futuristic dates. Further, we find that the larger the model, the faster the emergent date abstraction that heals date fragments is accomplished. Lastly, we observe a reasoning path that LLMs follow to assemble date fragments, typically differing from human interpretation (year \\(\rightarrow\\) month \\(\rightarrow\\) day). Our datasets and code are made publicly available \href\{https://github.com/gagan3012/date-fragments\}\{here\}.
