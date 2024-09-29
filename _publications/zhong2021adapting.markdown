---
layout: publication
title: Adapting Language Models For Zero45;shot Learning By Meta45;tuning On Dataset And Prompt Collections
authors: Zhong Ruiqi, Lee Kristy, Zhang Zheng, Klein Dan
conference: "Arxiv"
year: 2021
bibkey: zhong2021adapting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.04670"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Survey Paper', 'Training Techniques']
---
Large pre45;trained language models (LMs) such as GPT45;3 have acquired a surprising ability to perform zero45;shot learning. For example to classify sentiment without any training examples we can prompt the LM with the review and the label description Does the user like this movie and ask whether the next word is yes or no. However the next word prediction training objective is still misaligned with the target zero45;shot learning objective. To address this weakness we propose meta45;tuning which directly optimizes the zero45;shot learning objective by fine45;tuning pre45;trained language models on a collection of datasets. We focus on classification tasks and construct the meta45;dataset by aggregating 43 existing datasets and annotating 441 label descriptions in a question45;answering (QA) format. When evaluated on unseen tasks meta45;tuned models outperform a same45;sized QA model and the previous SOTA zero45;shot learning system based on natural language inference. Additionally increasing parameter count from 220M to 770M improves AUC45;ROC scores by 6.337; and we forecast that even larger models would perform better. Therefore measuring zero45;shot learning performance on language models out45;of45;the45;box might underestimate their true potential and community45;wide efforts on aggregating datasets and unifying their formats can help build models that answer prompts better.
