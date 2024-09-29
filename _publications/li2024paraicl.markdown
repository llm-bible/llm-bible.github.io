---
layout: publication
title: Paraicl Towards Robust Parallel In-context Learning
authors: Li Xingxuan, Nguyen Xuan-phi, Joty Shafiq, Bing Lidong
conference: "Arxiv"
year: 2024
bibkey: li2024paraicl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.00570"}
tags: ['Few Shot', 'In Context Learning', 'Prompting', 'RAG']
---
Large language models (LLMs) have become the norm in natural language processing (NLP) excelling in few-shot in-context learning (ICL) with their remarkable abilities. Nonetheless the success of ICL largely hinges on the choice of few-shot demonstration examples making the selection process increasingly crucial. Existing methods have delved into optimizing the quantity and semantic similarity of these examples to improve ICL performances. However our preliminary experiments indicate that the effectiveness of ICL is limited by the length of the input context. Moreover varying combinations of few-shot demonstration examples can significantly boost accuracy across different test samples. To address this we propose a novel method named parallel in-context learning (ParaICL) that effectively utilizes all demonstration examples without exceeding the manageable input context length. ParaICL employs parallel batching to distribute demonstration examples into different batches according to the semantic similarities of the questions in the demonstrations to the test question. It then computes normalized batch semantic scores for each batch. A weighted average semantic objective constrained by adaptive plausibility is applied to select the most appropriate tokens. Through extensive experiments we validate the effectiveness of ParaICL and conduct ablation studies to underscore its design rationale. We further demonstrate that ParaICL can seamlessly integrate with existing methods.
