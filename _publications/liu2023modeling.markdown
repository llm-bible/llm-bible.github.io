---
layout: publication
title: Modeling Uncertainty and Using Post-fusion as Fallback Improves Retrieval Augmented Generation with LLMs
authors: Liu Ye, Yavuz Semih, Meng Rui, Moorthy Meghana, Joty Shafiq, Xiong Caiming, Zhou Yingbo
conference: "Arxiv"
year: 2023
bibkey: liu2023modeling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.12574"}
tags: ['ARXIV', 'Applications', 'Chatgpt', 'Fine Tuning', 'GPT', 'LLM', 'Merging', 'Model Architecture', 'RAG']
---
The integration of retrieved passages and large language models (LLMs) such as ChatGPTs has significantly contributed to improving open-domain question answering. However there is still a lack of exploration regarding the optimal approach for incorporating retrieved passages into the answer generation process. This paper aims to fill this gap by investigating different methods of combining retrieved passages with LLMs to enhance answer generation. We begin by examining the limitations of a commonly-used concatenation approach. Surprisingly this approach often results in generating unknown outputs even when the correct document is among the top-k retrieved passages. To address this issue we explore four alternative strategies for integrating the retrieved passages with the LLMs. These strategies include two single-round methods that utilize chain-of-thought reasoning and two multi-round strategies that incorporate feedback loops. Through comprehensive analyses and experiments we provide insightful observations on how to effectively leverage retrieved passages to enhance the answer generation capability of LLMs.
