---
layout: publication
title: Transformer Quality In Linear Time
authors: Hua Weizhe, Dai Zihang, Liu Hanxiao, Le Quoc V.
conference: "Arxiv"
year: 2022
bibkey: hua2022transformer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2202.10447"}
tags: ['Attention Mechanism', 'BERT', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
We revisit the design choices in Transformers and propose methods to address their weaknesses in handling long sequences. First we propose a simple layer named gated attention unit which allows the use of a weaker single-head attention with minimal quality loss. We then propose a linear approximation method complementary to this new layer which is accelerator-friendly and highly competitive in quality. The resulting model named FLASH matches the perplexity of improved Transformers over both short (512) and long (8K) context lengths achieving training speedups of up to 4.9× on Wiki-40B and 12.1× on PG-19 for auto-regressive language modeling and 4.8× on C4 for masked language modeling.
