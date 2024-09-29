---
layout: publication
title: Towards A Holistic Evaluation Of Llms On Factual Knowledge Recall
authors: Yuan Jiaqing, Pan Lin, Hang Chung-wei, Guo Jiang, Jiang Jiarong, Min Bonan, Ng Patrick, Wang Zhiguo
conference: "Arxiv"
year: 2024
bibkey: yuan2024towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.16164"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Scaling Laws', 'Tools', 'Training Techniques']
---
Large language models (LLMs) have shown remarkable performance on a variety of NLP tasks and are being rapidly adopted in a wide range of use cases. It is therefore of vital importance to holistically evaluate the factuality of their generated outputs as hallucinations remain a challenging issue. In this work we focus on assessing LLMs ability to recall factual knowledge learned from pretraining and the factors that affect this ability. To that end we construct FACT45;BENCH a representative benchmark covering 20 domains 134 property types 3 answer types and different knowledge popularity levels. We benchmark 31 models from 10 model families and provide a holistic assessment of their strengths and weaknesses. We observe that instruction45;tuning hurts knowledge recall as pretraining45;only models consistently outperform their instruction45;tuned counterparts and positive effects of model scaling as larger models outperform smaller ones for all model families. However the best performance from GPT45;4 still represents a large gap with the upper45;bound. We additionally study the role of in45;context exemplars using counterfactual demonstrations which lead to significant degradation of factual knowledge recall for large models. By further decoupling model known and unknown knowledge we find the degradation is attributed to exemplars that contradict a models known knowledge as well as the number of such exemplars. Lastly we fine45;tune LLaMA45;7B in different settings of known and unknown knowledge. In particular fine45;tuning on a models known knowledge is beneficial and consistently outperforms fine45;tuning on unknown and mixed knowledge. We will make our benchmark publicly available.
