---
layout: publication
title: Dr3 Ask Large Language Models Not To Give Off45;topic Answers In Open Domain Multi45;hop Question Answering
authors: Gao Yuan, Zhu Yiheng, Cao Yuanbin, Zhou Yinzhi, Wu Zhen, Chen Yujie, Wu Shenglan, Hu Haoyuan, Dai Xinyu
conference: "Arxiv"
year: 2024
bibkey: gao2024ask
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.12393"}
tags: ['Applications', 'RAG', 'Reinforcement Learning', 'Tools']
---
Open Domain Multi45;Hop Question Answering (ODMHQA) plays a crucial role in Natural Language Processing (NLP) by aiming to answer complex questions through multi45;step reasoning over retrieved information from external knowledge sources. Recently Large Language Models (LLMs) have demonstrated remarkable performance in solving ODMHQA owing to their capabilities including planning reasoning and utilizing tools. However LLMs may generate off45;topic answers when attempting to solve ODMHQA namely the generated answers are irrelevant to the original questions. This issue of off45;topic answers accounts for approximately one45;third of incorrect answers yet remains underexplored despite its significance. To alleviate this issue we propose the Discriminate45;Re45;Compose45;Re45; Solve45;Re45;Decompose (Dr3) mechanism. Specifically the Discriminator leverages the intrinsic capabilities of LLMs to judge whether the generated answers are off45;topic. In cases where an off45;topic answer is detected the Corrector performs step45;wise revisions along the reversed reasoning chain (Re45;Compose45;Re45;Solve45;Re45;Decompose) until the final answer becomes on45;topic. Experimental results on the HotpotQA and 2WikiMultiHopQA datasets demonstrate that our Dr3 mechanism considerably reduces the occurrence of off45;topic answers in ODMHQA by nearly 1337; improving the performance in Exact Match (EM) by nearly 337; compared to the baseline method without the Dr3 mechanism.
