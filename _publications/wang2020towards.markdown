---
layout: publication
title: Towards Faithful Neural Table-to-Text Generation with Content-Matching Constraints
authors: Wang Zhenyi, Wang Xiaoyang, An Bang, Yu Dong, Chen Changyou
conference: "Proceedings of the"
year: 2020
bibkey: wang2020towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2005.00969"}
tags: ['Applications', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Transformer']
---
Text generation from a knowledge base aims to translate knowledge triples to natural language descriptions. Most existing methods ignore the faithfulness between a generated text description and the original table leading to generated information that goes beyond the content of the table. In this paper for the first time we propose a novel Transformer-based generation framework to achieve the goal. The core techniques in our method to enforce faithfulness include a new table-text optimal-transport matching loss and a table-text embedding similarity loss based on the Transformer model. Furthermore to evaluate faithfulness we propose a new automatic metric specialized to the table-to-text generation problem. We also provide detailed analysis on each component of our model in our experiments. Automatic and human evaluations show that our framework can significantly outperform state-of-the-art by a large margin.
