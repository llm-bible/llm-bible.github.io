---
layout: publication
title: 'Anchor-based Large Language Models'
authors: Jianhui Pang, Fanghua Ye, Derek Fai Wong, Xin He, Wanshun Chen, Longyue Wang
conference: "Arxiv"
year: 2024
bibkey: pang2024anchor
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.07616"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'RAG', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
Large language models (LLMs) predominantly employ decoder-only transformer
architectures, necessitating the retention of keys/values information for
historical tokens to provide contextual information and avoid redundant
computation. However, the substantial size and parameter volume of these LLMs
require massive GPU memory. This memory demand increases with the length of the
input text, leading to an urgent need for more efficient methods of information
storage and processing. This study introduces Anchor-based LLMs (AnLLMs), which
utilize an innovative anchor-based self-attention network (AnSAN) and also an
anchor-based inference strategy. This approach enables LLMs to compress
sequence information into an anchor token, reducing the keys/values cache and
enhancing inference efficiency. Experiments on question-answering benchmarks
reveal that AnLLMs maintain similar accuracy levels while achieving up to 99%
keys/values cache reduction and up to 3.5 times faster inference. Despite a
minor compromise in accuracy, the substantial enhancements of AnLLMs employing
the AnSAN technique in resource utilization and computational efficiency
underscore their potential for practical LLM applications.
