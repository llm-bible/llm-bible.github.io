---
layout: publication
title: "Calibrate Before Use: Improving Few-shot Performance Of Language Models"
authors: Zhao Tony Z., Wallace Eric, Feng Shi, Klein Dan, Singh Sameer
conference: "Arxiv"
year: 2021
bibkey: zhao2021calibrate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2102.09690"}
tags: ['Ethics And Bias', 'Few Shot', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
GPT-3 can perform numerous tasks when provided a natural language prompt that contains a few training examples. We show that this type of few-shot learning can be unstable the choice of prompt format training examples and even the order of the training examples can cause accuracy to vary from near chance to near state-of-the-art. We demonstrate that this instability arises from the bias of language models towards predicting certain answers e.g. those that are placed near the end of the prompt or are common in the pre-training data. To mitigate this we first estimate the models bias towards each answer by asking for its prediction when given the training prompt and a content-free test input such as N/A. We then fit calibration parameters that cause the prediction for this input to be uniform across answers. On a diverse set of tasks this contextual calibration procedure substantially improves GPT-3 and GPT-2s average accuracy (up to 30.037; absolute) and reduces variance across different choices of the prompt.
