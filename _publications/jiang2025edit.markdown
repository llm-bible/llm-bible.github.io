---
layout: publication
title: 'Anyedit: Edit Any Knowledge Encoded In Language Models'
authors: Houcheng Jiang, Junfeng Fang, Ningyu Zhang, Guojun Ma, Mingyang Wan, Xiang Wang, Xiangnan He, Tat-seng Chua
conference: "Arxiv"
year: 2025
bibkey: jiang2025edit
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.05628'}
tags: ['GPT', 'Tools', 'Pretraining Methods']
---
Large language models (LLMs) often produce incorrect or outdated information,
necessitating efficient and precise knowledge updates. Current model editing
methods, however, struggle with long-form knowledge in diverse formats, such as
poetry, code snippets, and mathematical derivations. These limitations arise
from their reliance on editing a single token's hidden state, a limitation we
term "efficacy barrier". To solve this, we propose AnyEdit, a new
autoregressive editing paradigm. It decomposes long-form knowledge into
sequential chunks and iteratively edits the key token in each chunk, ensuring
consistent and accurate outputs. Theoretically, we ground AnyEdit in the Chain
Rule of Mutual Information, showing its ability to update any knowledge within
LLMs. Empirically, it outperforms strong baselines by 21.5% on benchmarks
including UnKEBench, AKEW, and our new EditEverything dataset for long-form
diverse-formatted knowledge. Additionally, AnyEdit serves as a plug-and-play
framework, enabling current editing methods to update knowledge with arbitrary
length and format, significantly advancing the scope and practicality of LLM
knowledge editing.
