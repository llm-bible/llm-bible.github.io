---
layout: publication
title: PEGASUS Pre45;training With Extracted Gap45;sentences For Abstractive Summarization
authors: Zhang Jingqing, Zhao Yao, Saleh Mohammad, Liu Peter J.
conference: "Arxiv"
year: 2019
bibkey: zhang2019pre
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1912.08777"}
tags: ['Applications', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Recent work pre45;training Transformers with self45;supervised objectives on large text corpora has shown great success when fine45;tuned on downstream NLP tasks including text summarization. However pre45;training objectives tailored for abstractive text summarization have not been explored. Furthermore there is a lack of systematic evaluation across diverse domains. In this work we propose pre45;training large Transformer45;based encoder45;decoder models on massive text corpora with a new self45;supervised objective. In PEGASUS important sentences are removed/masked from an input document and are generated together as one output sequence from the remaining sentences similar to an extractive summary. We evaluated our best PEGASUS model on 12 downstream summarization tasks spanning news science stories instructions emails patents and legislative bills. Experiments demonstrate it achieves state45;of45;the45;art performance on all 12 downstream datasets measured by ROUGE scores. Our model also shows surprising performance on low45;resource summarization surpassing previous state45;of45;the45;art results on 6 datasets with only 1000 examples. Finally we validated our results using human evaluation and show that our model summaries achieve human performance on multiple datasets.
