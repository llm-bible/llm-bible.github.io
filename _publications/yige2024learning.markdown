---
layout: publication
title: 'DRUM: Learning Demonstration Retriever For Large Multi-modal Models'
authors: Ellen Yi-ge, Jiechao Gao, Wei Han, Wei Zhu
conference: "Arxiv"
year: 2024
bibkey: yige2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.07619"}
tags: ['Tools', 'Reinforcement Learning', 'Training Techniques', 'Multimodal Models', 'Prompting', 'In-Context Learning']
---
Recently, large language models (LLMs) have demonstrated impressive
capabilities in dealing with new tasks with the help of in-context learning
(ICL). In the study of Large Vision-Language Models (LVLMs), when implementing
ICL, researchers usually adopts the naive strategies like fixed demonstrations
across different samples, or selecting demonstrations directly via a
visual-language embedding model. These methods does not guarantee the
configured demonstrations fit the need of the LVLMs. To address this issue, we
now propose a novel framework, \underline\{d\}emonstration \underline\{r\}etriever
for large m\underline\{u\}lti-modal \underline\{m\}odel (DRUM), which fine-tunes
the visual-language embedding model to better meet the LVLM's needs. First, we
discuss the retrieval strategies for a visual-language task, assuming an
embedding model is given. And we propose to concate the image and text
embeddings to enhance the retrieval performance. Second, we propose to re-rank
the demonstrations retrieved by the embedding model via the LVLM's feedbacks,
and calculate a list-wise ranking loss for training the embedding model. Third,
we propose an iterative demonstration mining strategy to improve the training
of the embedding model. Through extensive experiments on 3 types of
visual-language tasks, 7 benchmark datasets, our DRUM framework is proven to be
effective in boosting the LVLM's in-context learning performance via retrieving
more proper demonstrations.
