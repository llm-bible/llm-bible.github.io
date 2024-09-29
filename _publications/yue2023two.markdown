---
layout: publication
title: Llamarec Two45;stage Recommendation Using Large Language Models For Ranking
authors: Zhenrui Yue, Sara Rabhi, Gabriel De Souza Pereira Moreira, Dong Wang, Even Oldridge
conference: "Arxiv"
year: 2023
bibkey: yue2023two
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2311.02089v1"}
tags: ['Efficiency And Optimization', 'GPT', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Recently large language models (LLMs) have exhibited significant progress in language understanding and generation. By leveraging textual features customized LLMs are also applied for recommendation and demonstrate improvements across diverse recommendation scenarios. Yet the majority of existing methods perform training45;free recommendation that heavily relies on pretrained knowledge (e.g. movie recommendation). In addition inference on LLMs is slow due to autoregressive generation rendering existing methods less effective for real45;time recommendation. As such we propose a two45;stage framework using large language models for ranking45;based recommendation (LlamaRec). In particular we use small45;scale sequential recommenders to retrieve candidates based on the user interaction history. Then both history and retrieved items are fed to the LLM in text via a carefully designed prompt template. Instead of generating next45;item titles we adopt a verbalizer45;based approach that transforms output logits into probability distributions over the candidate items. Therefore the proposed LlamaRec can efficiently rank items without generating long text. To validate the effectiveness of the proposed framework we compare against state45;of45;the45;art baseline methods on benchmark datasets. Our experimental results demonstrate the performance of LlamaRec which consistently achieves superior performance in both recommendation performance and efficiency.
