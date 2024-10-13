---
layout: publication
title: 'Online Adaptation Of Language Models With A Memory Of Amortized Contexts'
authors: Tack Jihoon, Kim Jaehyung, Mitchell Eric, Shin Jinwoo, Teh Yee Whye, Schwarz Jonathan Richard
conference: "Arxiv"
year: 2024
bibkey: tack2024online
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.04317"}
  - {name: "Code", url: "https://github.com/jihoontack/MAC"}
tags: ['Applications', 'Efficiency And Optimization', 'Has Code', 'Reinforcement Learning', 'Tools', 'Uncategorized']
---
Due to the rapid generation and dissemination of information, large language
models (LLMs) quickly run out of date despite enormous development costs. Due
to this crucial need to keep models updated, online learning has emerged as a
critical necessity when utilizing LLMs for real-world applications. However,
given the ever-expanding corpus of unseen documents and the large parameter
space of modern LLMs, efficient adaptation is essential. To address these
challenges, we propose Memory of Amortized Contexts (MAC), an efficient and
effective online adaptation framework for LLMs with strong knowledge retention.
We propose an amortized feature extraction and memory-augmentation approach to
compress and extract information from new documents into compact modulations
stored in a memory bank. When answering questions, our model attends to and
extracts relevant knowledge from this memory bank. To learn informative
modulations in an efficient manner, we utilize amortization-based
meta-learning, which substitutes the optimization process with a single forward
pass of the encoder. Subsequently, we learn to choose from and aggregate
selected documents into a single modulation by conditioning on the question,
allowing us to adapt a frozen language model during test time without requiring
further gradient updates. Our experiment demonstrates the superiority of MAC in
multiple aspects, including online adaptation performance, time, and memory
efficiency. Code is available at: https://github.com/jihoontack/MAC.
