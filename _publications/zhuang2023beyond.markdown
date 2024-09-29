---
layout: publication
title: Beyond Yes And No Improving Zero45;shot LLM Rankers Via Scoring Fine45;grained Relevance Labels
authors: Zhuang Honglei, Qin Zhen, Hui Kai, Wu Junru, Yan Le, Wang Xuanhui, Bendersky Michael
conference: "Arxiv"
year: 2023
bibkey: zhuang2023beyond
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.14122"}
tags: ['Ethics And Bias', 'Prompting']
---
Zero45;shot text rankers powered by recent LLMs achieve remarkable ranking performance by simply prompting. Existing prompts for pointwise LLM rankers mostly ask the model to choose from binary relevance labels like Yes and No. However the lack of intermediate relevance label options may cause the LLM to provide noisy or biased answers for documents that are partially relevant to the query. We propose to incorporate fine45;grained relevance labels into the prompt for LLM rankers enabling them to better differentiate among documents with different levels of relevance to the query and thus derive a more accurate ranking. We study two variants of the prompt template coupled with different numbers of relevance levels. Our experiments on 8 BEIR data sets show that adding fine45;grained relevance labels significantly improves the performance of LLM rankers.
