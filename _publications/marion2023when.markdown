---
layout: publication
title: When Less Is More\: Investigating Data Pruning For Pretraining Llms At Scale
authors: Marion Max, Üstün Ahmet, Pozzobon Luiza, Wang Alex, Fadaee Marzieh, Hooker Sara
conference: "Arxiv"
year: 2023
bibkey: marion2023when
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.04564"}
tags: ['Efficiency And Optimization', 'Pretraining Methods', 'Pruning', 'Tools', 'Training Techniques']
---
Large volumes of text data have contributed significantly to the development of large language models (LLMs) in recent years. This data is typically acquired by scraping the internet leading to pretraining datasets comprised of noisy web text. To date efforts to prune these datasets down to a higher quality subset have relied on hand-crafted heuristics encoded as rule-based filters. In this work we take a wider view and explore scalable estimates of data quality that can be used to systematically measure the quality of pretraining data. We perform a rigorous comparison at scale of the simple data quality estimator of perplexity as well as more sophisticated and computationally intensive estimates of the Error L2-Norm and memorization. These metrics are used to rank and prune pretraining corpora and we subsequently compare LLMs trained on these pruned datasets. Surprisingly we find that the simple technique of perplexity outperforms our more computationally expensive scoring methods. We improve over our no-pruning baseline while training on as little as 3037; of the original training dataset. Our work sets the foundation for unexplored strategies in automatically curating high quality corpora and suggests the majority of pretraining data can be removed while retaining performance.
