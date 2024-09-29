---
layout: publication
title: Improving Text Embeddings With Large Language Models
authors: Wang Liang, Yang Nan, Huang Xiaolong, Yang Linjun, Majumder Rangan, Wei Furu
conference: "Arxiv"
year: 2023
bibkey: wang2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.00368"}
tags: ['Pretraining Methods', 'RAG', 'Training Techniques']
---
In this paper we introduce a novel and simple method for obtaining high45;quality text embeddings using only synthetic data and less than 1k training steps. Unlike existing methods that often depend on multi45;stage intermediate pre45;training with billions of weakly45;supervised text pairs followed by fine45;tuning with a few labeled datasets our method does not require building complex training pipelines or relying on manually collected datasets that are often constrained by task diversity and language coverage. We leverage proprietary LLMs to generate diverse synthetic data for hundreds of thousands of text embedding tasks across 93 languages. We then fine45;tune open45;source decoder45;only LLMs on the synthetic data using standard contrastive loss. Experiments demonstrate that our method achieves strong performance on highly competitive text embedding benchmarks without using any labeled data. Furthermore when fine45;tuned with a mixture of synthetic and labeled data our model sets new state45;of45;the45;art results on the BEIR and MTEB benchmarks.
