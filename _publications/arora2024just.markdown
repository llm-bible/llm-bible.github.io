---
layout: publication
title: 'Just Read Twice: Closing The Recall Gap For Recurrent Language Models'
authors: Simran Arora, Aman Timalsina, Aaryan Singhal, Benjamin Spector, Sabri Eyuboglu, Xinyi Zhao, Ashish Rao, Atri Rudra, Christopher Ré
conference: "Arxiv"
year: 2024
bibkey: arora2024just
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.05483"}
tags: ['Model Architecture', 'Tools', 'RAG', 'Merging', 'In-Context Learning', 'Pretraining Methods', 'Transformer', 'Prompting', 'Attention Mechanism']
---
Recurrent large language models that compete with Transformers in language
modeling perplexity are emerging at a rapid rate (e.g., Mamba, RWKV).
Excitingly, these architectures use a constant amount of memory during
inference. However, due to the limited memory, recurrent LMs cannot recall and
use all the information in long contexts leading to brittle in-context learning
(ICL) quality. A key challenge for efficient LMs is selecting what information
to store versus discard. In this work, we observe the order in which
information is shown to the LM impacts the selection difficulty. To formalize
this, we show that the hardness of information recall reduces to the hardness
of a problem called set disjointness (SD), a quintessential problem in
communication complexity that requires a streaming algorithm (e.g., recurrent
model) to decide whether inputted sets are disjoint. We empirically and
theoretically show that the recurrent memory required to solve SD changes with
set order, i.e., whether the smaller set appears first in-context. Our analysis
suggests, to mitigate the reliance on data order, we can put information in the
right order in-context or process prompts non-causally. Towards that end, we
propose: (1) JRT-Prompt, where context gets repeated multiple times in the
prompt, effectively showing the model all data orders. This gives \\(11.0 \pm
1.3\\) points of improvement, averaged across \\(16\\) recurrent LMs and the \\(6\\) ICL
tasks, with \\(11.9\times\\) higher throughput than FlashAttention-2 for generation
prefill (length \\(32\\)k, batch size \\(16\\), NVidia H100). We then propose (2)
JRT-RNN, which uses non-causal prefix-linear-attention to process prompts and
provides \\(99%\\) of Transformer quality at \\(360\\)M params., \\(30\\)B tokens and
\\(96%\\) at \\(1.3\\)B params., \\(50\\)B tokens on average across the tasks, with
\\(19.2\times\\) higher throughput for prefill than FA2.
