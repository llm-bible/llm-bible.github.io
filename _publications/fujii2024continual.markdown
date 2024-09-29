---
layout: publication
title: Continual Pre45;training For Cross45;lingual LLM Adaptation Enhancing Japanese Language Capabilities
authors: Fujii Kazuki, Nakamura Taishi, Loem Mengsay, Iida Hiroki, Ohi Masanari, Hattori Kakeru, Shota Hirai, Mizuki Sakae, Yokota Rio, Okazaki Naoaki
conference: "Arxiv"
year: 2024
bibkey: fujii2024continual
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.17790"}
tags: ['Applications', 'Efficiency And Optimization', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Cross45;lingual continual pre45;training of large language models (LLMs) initially trained on English corpus allows us to leverage the vast amount of English language resources and reduce the pre45;training cost. In this study we constructed Swallow an LLM with enhanced Japanese capability by extending the vocabulary of Llama 2 to include Japanese characters and conducting continual pre45;training on a large Japanese web corpus. Experimental results confirmed that the performance on Japanese tasks drastically improved through continual pre45;training and the performance monotonically increased with the amount of training data up to 100B tokens. Consequently Swallow achieved superior performance compared to other LLMs that were trained from scratch in English and Japanese. An analysis of the effects of continual pre45;training revealed that it was particularly effective for Japanese question answering tasks. Furthermore to elucidate effective methodologies for cross45;lingual continual pre45;training from English to Japanese we investigated the impact of vocabulary expansion and the effectiveness of incorporating parallel corpora. The results showed that the efficiency gained through vocabulary expansion had no negative impact on performance except for the summarization task and that the combined use of parallel corpora enhanced translation ability.
