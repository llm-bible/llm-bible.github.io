---
layout: publication
title: 'Jepa4rec: Learning Effective Language Representations For Sequential Recommendation Via Joint Embedding Predictive Architecture'
authors: Minh-anh Nguyen, Dung D. Le
conference: "Arxiv"
year: 2025
bibkey: nguyen2025learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2504.10512"}
tags: ['Multimodal Models', 'Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Language Modeling', 'Pretraining Methods', 'BERT', 'Transformer', 'Pre-Training']
---
Language representation learning has emerged as a promising approach for
sequential recommendation, thanks to its ability to learn generalizable
representations. However, despite its advantages, this approach still struggles
with data sparsity and a limited understanding of common-sense user
preferences. To address these limitations, we propose \\(\textbf\{JEPA4Rec\}\\), a
framework that combines \\(\textbf\{J\}\\)oint \\(\textbf\{E\}\\)mbedding
\\(\textbf\{P\}\\)redictive \\(\textbf\{A\}\\)rchitecture with language modeling of item
textual descriptions. JEPA4Rec captures semantically rich and transferable
representations, improving recommendation performance and reducing reliance on
large-scale pre-training data. Specifically, JEPA4Rec represents items as text
sentences by flattening descriptive information such as \\(\textit\{title,
category\}\\), and other attributes. To encode these sentences, we employ a
bidirectional Transformer encoder with modified embedding layers tailored for
capturing item information in recommendation datasets. We apply masking to text
sentences and use them to predict the representations of the unmasked
sentences, helping the model learn generalizable item embeddings. To further
improve recommendation performance and language understanding, we employ a
two-stage training strategy incorporating self-supervised learning losses.
Experiments on six real-world datasets demonstrate that JEPA4Rec consistently
outperforms state-of-the-art methods, particularly in cross-domain,
cross-platform, and low-resource scenarios.
