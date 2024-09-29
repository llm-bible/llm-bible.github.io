---
layout: publication
title: Attention Instruction Amplifying Attention In The Middle Via Prompting
authors: Zhang Meiru, Meng Zaiqiao, Collier Nigel
conference: "Arxiv"
year: 2024
bibkey: zhang2024attention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.17095"}
tags: ['Applications', 'Attention Mechanism', 'Ethics And Bias', 'Model Architecture', 'Prompting', 'RAG']
---
The context window of large language models has been extended to 128k tokens or more. However language models still suffer from position bias and have difficulty in accessing and using the middle part of the context due to the lack of attention. We examine the relative position awareness of LLMs and the feasibility of mitigating disproportional attention through prompting. We augment the original task instruction with (texttt)attention instructions that direct language models to allocate more attention towards a selected segment of the context. We conduct a comprehensive investigation on multi-document question answering task with both position-based and index-based instructions. We find that language models do not have relative position awareness of the context. Nevertheless they demonstrate the capacity to adapt attention to a specific segment using matching indexes. Our analysis contributes to a deeper understanding of position bias in LLMs and provides a pathway to mitigate this bias by instruction thus benefiting LLMs in locating and utilizing relevant information from retrieved documents in RAG applications.
