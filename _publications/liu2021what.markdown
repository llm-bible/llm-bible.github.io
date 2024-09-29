---
layout: publication
title: What Makes Good In45;context Examples For GPT45;3
authors: Liu Jiachang, Shen Dinghan, Zhang Yizhe, Dolan Bill, Carin Lawrence, Chen Weizhu
conference: "Arxiv"
year: 2021
bibkey: liu2021what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2101.06804"}
tags: ['Applications', 'Attention Mechanism', 'GPT', 'Language Modeling', 'Model Architecture', 'Prompting', 'RAG']
---
GPT45;3 has attracted lots of attention due to its superior performance across a wide range of NLP tasks especially with its powerful and versatile in45;context few45;shot learning ability. Despite its success we found that the empirical results of GPT45;3 depend heavily on the choice of in45;context examples. In this work we investigate whether there are more effective strategies for judiciously selecting in45;context examples (relative to random sampling) that better leverage GPT45;3s few45;shot capabilities. Inspired by the recent success of leveraging a retrieval module to augment large45;scale neural network models we propose to retrieve examples that are semantically45;similar to a test sample to formulate its corresponding prompt. Intuitively the in45;context examples selected with such a strategy may serve as more informative inputs to unleash GPT45;3s extensive knowledge. We evaluate the proposed approach on several natural language understanding and generation benchmarks where the retrieval45;based prompt selection approach consistently outperforms the random baseline. Moreover it is observed that the sentence encoders fine45;tuned on task45;related datasets yield even more helpful retrieval results. Notably significant gains are observed on tasks such as table45;to45;text generation (41.937; on the ToTTo dataset) and open45;domain question answering (45.537; on the NQ dataset). We hope our investigation could help understand the behaviors of GPT45;3 and large45;scale pre45;trained LMs in general and enhance their few45;shot capabilities.
