---
layout: publication
title: 'Ground Every Sentence: Improving Retrieval-augmented Llms With Interleaved Reference-claim Generation'
authors: Sirui Xia, Xintao Wang, Jiaqing Liang, Yifei Zhang, Weikang Zhou, Jiaji Deng, Fei Yu, Yanghua Xiao
conference: "Arxiv"
year: 2024
bibkey: xia2024ground
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.01796'}
tags: ['Reinforcement Learning', 'RAG', 'Language Modeling', 'Applications']
---
Retrieval-Augmented Generation (RAG) has been widely adopted to enhance Large Language Models (LLMs) in knowledge-intensive tasks. To enhance credibility and verifiability in RAG systems, Attributed Text Generation (ATG) is proposed, which provides citations to retrieval knowledge in LLM-generated responses. Prior methods mainly adopt coarse-grained attributions, with passage-level or paragraph-level references or citations, which fall short in verifiability. This paper proposes ReClaim (Refer & Claim), a fine-grained ATG method that alternates the generation of references and answers step by step. Different from previous coarse-grained attribution, ReClaim provides sentence-level citations in long-form question-answering tasks. With extensive experiments, we verify the effectiveness of ReClaim in extensive settings, achieving a citation accuracy rate of 90%.
