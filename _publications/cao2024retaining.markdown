---
layout: publication
title: Retaining Key Information under High Compression Ratios Query-Guided Compressor for LLMs
authors: Cao Zhiwei, Cao Qian, Lu Yu, Peng Ningxin, Huang Luyang, Cheng Shanbo, Su Jinsong
conference: "Arxiv"
year: 2024
bibkey: cao2024retaining
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02376"}
tags: ['Applications', 'RAG', 'Reinforcement Learning']
---
The growing popularity of Large Language Models has sparked interest in context compression for Large Language Models (LLMs). However the performance of previous methods degrades dramatically as compression ratios increase sometimes even falling to the closed-book level. This decline can be attributed to the loss of key information during the compression process. Our preliminary study supports this hypothesis emphasizing the significance of retaining key information to maintain model performance under high compression ratios. As a result we introduce Query-Guided Compressor (QGC) which leverages queries to guide the context compression process effectively preserving key information within the compressed context. Additionally we employ a dynamic compression strategy. We validate the effectiveness of our proposed QGC on the Question Answering task including NaturalQuestions TriviaQA and HotpotQA datasets. Experimental results show that QGC can consistently perform well even at high compression ratios which also offers significant benefits in terms of inference cost and throughput.
