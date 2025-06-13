---
layout: publication
title: 'O\(^2\)-searcher: A Searching-based Agent Model For Open-domain Open-ended Question Answering'
authors: Jianbiao Mei, Tao Hu, Daocheng Fu, Licheng Wen, Xuemeng Yang, Rong Wu, Pinlong Cai, Xinyu Cai, Xing Gao, Yu Yang, Chengjun Xie, Botian Shi, Yong Liu, Yu Qiao
conference: "Arxiv"
year: 2025
bibkey: mei2025searching
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16582"}
tags: ['Agentic', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Large Language Models (LLMs), despite their advancements, are fundamentally limited by their static parametric knowledge, hindering performance on tasks requiring open-domain up-to-date information. While enabling LLMs to interact with external knowledge environments is a promising solution, current efforts primarily address closed-end problems. Open-ended questions, which characterized by lacking a standard answer or providing non-unique and diverse answers, remain underexplored. To bridge this gap, we present O\\(^2\\)-Searcher, a novel search agent leveraging reinforcement learning to effectively tackle both open-ended and closed-ended questions in the open domain. O\\(^2\\)-Searcher leverages an efficient, locally simulated search environment for dynamic knowledge acquisition, effectively decoupling the external world knowledge from model's sophisticated reasoning processes. It employs a unified training mechanism with meticulously designed reward functions, enabling the agent to identify problem types and adapt different answer generation strategies. Furthermore, to evaluate performance on complex open-ended tasks, we construct O\\(^2\\)-QA, a high-quality benchmark featuring 300 manually curated, multi-domain open-ended questions with associated web page caches. Extensive experiments show that O\\(^2\\)-Searcher, using only a 3B model, significantly surpasses leading LLM agents on O\\(^2\\)-QA. It also achieves SOTA results on various closed-ended QA benchmarks against similarly-sized models, while performing on par with much larger ones.
