---
layout: publication
title: Generate labeled training data using Prompt Programming and GPT-3. An example of Big Five Personality Classification
authors: Chen Eason
conference: "Arxiv"
year: 2023
bibkey: chen2023generate
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.12279"}
tags: ['ARXIV', 'GPT', 'Model Architecture', 'Transformer']
---
We generated 25000 conversations labeled with Big Five Personality traits using prompt programming at GPT-3. Then we train Big Five classification models with these data and evaluate them with 2500 data from generated dialogues and real conversational datasets labeled in Big Five by human annotators. The results indicated that this approach is promising for creating effective training data. We then compare the performance by different training approaches and models. Our results suggest that using Adapter-Transformers and transfer learning from pre-trained RoBERTa sentiment analysis model will perform best with the generated data. Our best model obtained an accuracy of 0.71 in generated data and 0.65 in real datasets. Finally we discuss this approachs potential limitations and confidence metric.
