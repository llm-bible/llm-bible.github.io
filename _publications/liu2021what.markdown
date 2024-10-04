---
layout: publication
title: 'What Makes Good In-context Examples For GPT-\(3\)?'
authors: Liu Jiachang, Shen Dinghan, Zhang Yizhe, Dolan Bill, Carin Lawrence, Chen Weizhu
conference: "Arxiv"
year: 2021
bibkey: liu2021what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2101.06804"}
tags: ['Applications', 'Attention Mechanism', 'Few Shot', 'GPT', 'Language Modeling', 'Model Architecture', 'Prompting', 'RAG']
---
GPT-\\(3\\) has attracted lots of attention due to its superior performance across a wide range of NLP tasks, especially with its powerful and versatile in-context few-shot learning ability. Despite its success, we found that the empirical results of GPT-\\(3\\) depend heavily on the choice of in-context examples. In this work, we investigate whether there are more effective strategies for judiciously selecting in-context examples (relative to random sampling) that better leverage GPT-\\(3\\)'s few-shot capabilities. Inspired by the recent success of leveraging a retrieval module to augment large-scale neural network models, we propose to retrieve examples that are semantically-similar to a test sample to formulate its corresponding prompt. Intuitively, the in-context examples selected with such a strategy may serve as more informative inputs to unleash GPT-\\(3\\)'s extensive knowledge. We evaluate the proposed approach on several natural language understanding and generation benchmarks, where the retrieval-based prompt selection approach consistently outperforms the random baseline. Moreover, it is observed that the sentence encoders fine-tuned on task-related datasets yield even more helpful retrieval results. Notably, significant gains are observed on tasks such as table-to-text generation (41.9&#37; on the ToTTo dataset) and open-domain question answering (45.5&#37; on the NQ dataset). We hope our investigation could help understand the behaviors of GPT-\\(3\\) and large-scale pre-trained LMs in general and enhance their few-shot capabilities.
