---
layout: publication
title: Aligning a medium-size GPT model in English to a small closed domain in Spanish
authors: Navarrete-parra Oscar R., Uc-cetina Victor, Reyes-magana Jorge
conference: "Arxiv"
year: 2023
bibkey: navarreteparra2023aligning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.17649"}
tags: ['ARXIV', 'Applications', 'GPT']
---
In this paper we propose a methodology to align a medium-sized GPT model originally trained in English for an open domain to a small closed domain in Spanish. The application for which the model is finely tuned is the question answering task. To achieve this we also needed to train and implement another neural network (which we called the reward model) that could score and determine whether an answer is appropriate for a given question. This component served to improve the decoding and generation of the answers of the system. Numerical metrics such as BLEU and perplexity were used to evaluate the model and human judgment was also used to compare the decoding technique with others. Finally the results favored the proposed method and it was determined that it is feasible to use a reward model to align the generation of responses.
