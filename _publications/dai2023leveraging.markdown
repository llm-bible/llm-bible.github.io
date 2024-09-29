---
layout: publication
title: Auggpt Leveraging Chatgpt For Text Data Augmentation
authors: Dai Haixing, Liu Zhengliang, Liao Wenxiong, Huang Xiaoke, Cao Yihan, Wu Zihao, Zhao Lin, Xu Shaochen, Liu Wei, Liu Ninghao, Li Sheng, Zhu Dajiang, Cai Hongmin, Sun Lichao, Li Quanzheng, Shen Dinggang, Liu Tianming, Li Xiang
conference: "Arxiv"
year: 2023
bibkey: dai2023leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2302.13007"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Text data augmentation is an effective strategy for overcoming the challenge of limited sample sizes in many natural language processing (NLP) tasks. This challenge is especially prominent in the few45;shot learning scenario where the data in the target domain is generally much scarcer and of lowered quality. A natural and widely45;used strategy to mitigate such challenges is to perform data augmentation to better capture the data invariance and increase the sample size. However current text data augmentation methods either cant ensure the correct labeling of the generated data (lacking faithfulness) or cant ensure sufficient diversity in the generated data (lacking compactness) or both. Inspired by the recent success of large language models especially the development of ChatGPT which demonstrated improved language comprehension abilities in this work we propose a text data augmentation approach based on ChatGPT (named AugGPT). AugGPT rephrases each sentence in the training samples into multiple conceptually similar but semantically different samples. The augmented samples can then be used in downstream model training. Experiment results on few45;shot learning text classification tasks show the superior performance of the proposed AugGPT approach over state45;of45;the45;art text data augmentation methods in terms of testing accuracy and distribution of the augmented samples.
