---
layout: publication
title: Mt45;ladder A Model45;agnostic Framework Boosting Llm45;based Machine Translation To The Next Level
authors: Feng Zhaopeng, Zhang Yan, Chen Ruizhe, Meng Zijie, Liu Zuozhu
conference: "Arxiv"
year: 2024
bibkey: feng2024mt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.15741"}
  - {name: "Code", url: "https://github.com/fzp0424/Ladder"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'RAG', 'Tools', 'Training Techniques']
---
General45;purpose Large Language Models (LLMs) like GPT45;4 have achieved remarkable advancements in machine translation (MT) by leveraging extensive web content. On the other hand translation45;specific LLMs are built by pre45;training on domain45;specific monolingual corpora and fine45;tuning with human45;annotated translation data. Despite the superior performance these methods either demand an unprecedented scale of computing and data or substantial human editing and annotation efforts. In this paper we develop MT45;Ladder a novel model45;agnostic and cost45;effective tool to refine the performance of general LLMs for MT. MT45;Ladder is trained on pseudo45;refinement triplets which can be easily obtained from existing LLMs without additional human cost. During training we propose a hierarchical fine45;tuning strategy with an easy45;to45;hard schema improving MT45;Ladders refining performance progressively. The trained MT45;Ladder can be seamlessly integrated with any general45;purpose LLMs to boost their translation performance. By utilizing Gemma45;2B/7B as the backbone MT45;Ladder45;2B can elevate raw translations to the level of top45;tier open45;source models (e.g. refining BigTranslate45;13B with +6.91 BLEU and +3.52 COMET for XX45;En) and MT45;Ladder45;7B can further enhance model performance to be on par with the state45;of45;the45;art GPT45;4. Extensive ablation and analysis corroborate the effectiveness of MT45;Ladder in diverse settings. Our code is available at https://github.com/fzp0424/Ladder
