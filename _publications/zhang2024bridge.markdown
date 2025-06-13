---
layout: publication
title: 'Bridge-coder: Unlocking Llms'' Potential To Overcome Language Gaps In Low-resource Code'
authors: Jipeng Zhang, Jianshu Zhang, Yuanzhe Li, Renjie Pi, Rui Pan, Runtao Liu, Ziqiang Zheng, Tong Zhang
conference: "Arxiv"
year: 2024
bibkey: zhang2024bridge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.18957"}
tags: ['Training Techniques', 'Reinforcement Learning', 'RAG', 'Prompting', 'In-Context Learning']
---
Large Language Models (LLMs) demonstrate strong proficiency in generating
code for high-resource programming languages (HRPLs) like Python but struggle
significantly with low-resource programming languages (LRPLs) such as Racket or
D. This performance gap deepens the digital divide, preventing developers using
LRPLs from benefiting equally from LLM advancements and reinforcing disparities
in innovation within underrepresented programming communities. While generating
additional training data for LRPLs is promising, it faces two key challenges:
manual annotation is labor-intensive and costly, and LLM-generated LRPL code is
often of subpar quality. The underlying cause of this issue is the gap between
natural language to programming language gap (NL-PL Gap), which is especially
pronounced in LRPLs due to limited aligned data. In this work, we introduce a
novel approach called Bridge-Coder, which leverages LLMs' intrinsic
capabilities to enhance the performance on LRPLs. Our method consists of two
key stages. Bridge Generation, where we create high-quality dataset by
utilizing LLMs' general knowledge understanding, proficiency in HRPLs, and
in-context learning abilities. Then, we apply the Bridged Alignment, which
progressively improves the alignment between NL instructions and LRPLs.
Experimental results across multiple LRPLs show that Bridge-Coder significantly
enhances model performance, demonstrating the effectiveness and generalization
of our approach. Furthermore, we offer a detailed analysis of the key
components of our method, providing valuable insights for future work aimed at
addressing the challenges associated with LRPLs.
