---
layout: publication
title: Prefix45;tuning Optimizing Continuous Prompts For Generation
authors: Xiang Lisa Li, Percy Liang
conference: "Arxiv"
year: 2021
bibkey: lisa2021prefix
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2101.00190v1"}
tags: ['Applications', 'GPT', 'Language Modeling', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
Fine45;tuning is the de facto way to leverage large pretrained language models to perform downstream tasks. However it modifies all the language model parameters and therefore necessitates storing a full copy for each task. In this paper we propose prefix45;tuning a lightweight alternative to fine45;tuning for natural language generation tasks which keeps language model parameters frozen but optimizes a small continuous task45;specific vector (called the prefix). Prefix45;tuning draws inspiration from prompting allowing subsequent tokens to attend to this prefix as if it were virtual tokens. We apply prefix45;tuning to GPT45;2 for table45;to45;text generation and to BART for summarization. We find that by learning only 0.137; of the parameters prefix45;tuning obtains comparable performance in the full data setting outperforms fine45;tuning in low45;data settings and extrapolates better to examples with topics unseen during training.
