---
layout: publication
title: SSP Self45;supervised Prompting For Cross45;lingual Transfer To Low45;resource Languages Using Large Language Models
authors: Rathore Vipul, Deb Aniruddha, Chandresh Ankish, Singla Parag, Mausam
conference: "Arxiv"
year: 2024
bibkey: rathore2024self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18880"}
tags: ['Pretraining Methods', 'Prompting', 'RAG', 'Reinforcement Learning', 'Training Techniques']
---
Recently very large language models (LLMs) have shown exceptional performance on several English NLP tasks with just in45;context learning (ICL) but their utility in other languages is still underexplored. We investigate their effectiveness for NLP tasks in low45;resource languages (LRLs) especially in the setting of zero45;labelled cross45;lingual transfer (045;CLT) where no labelled training data for the target language is available 45;45; however training data from one or more related medium45;resource languages (MRLs) is utilized alongside the available unlabeled test data for a target language. We introduce Self45;Supervised Prompting (SSP) a novel ICL approach tailored for the 045;CLT setting. SSP is based on the key observation that LLMs output more accurate labels if in45;context exemplars are from the target language (even if their labels are slightly noisy). To operationalize this since target language training data is not available in 045;CLT SSP operates in two stages. In Stage I using source MRL training data target languages test data is noisily labeled. In Stage II these noisy test data points are used as exemplars in ICL for further improved labelling. Additionally our implementation of SSP uses a novel Integer Linear Programming (ILP)45;based exemplar selection that balances similarity prediction confidence (when available) and label coverage. Experiments on three tasks and eleven LRLs (from three regions) demonstrate that SSP strongly outperforms existing SOTA fine45;tuned and prompting45;based baselines in 045;CLT setup.
