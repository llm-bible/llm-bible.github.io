---
layout: publication
title: "Enhancing Black-box Few-shot Text Classification With Prompt-based Data Augmentation"
authors: Luo Danqing, Zhang Chen, Xu Jiahui, Wang Bin, Chen Yiming, Zhang Yan, Li Haizhou
conference: "Arxiv"
year: 2023
bibkey: luo2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13785"}
tags: ['Few Shot', 'GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
Training or finetuning large-scale language models (LLMs) such as GPT-3 requires substantial computation resources motivating recent efforts to explore parameter-efficient adaptation to downstream tasks. One practical area of research is to treat these models as black boxes and interact with them through their inference APIs. In this paper we investigate how to optimize few-shot text classification without accessing the gradients of the LLMs. To achieve this we treat the black-box model as a feature extractor and train a classifier with the augmented text data. Data augmentation is performed using prompt-based finetuning on an auxiliary language model with a much smaller parameter size than the black-box model. Through extensive experiments on eight text classification datasets we show that our approach dubbed BT-Classifier significantly outperforms state-of-the-art black-box few-shot learners and performs on par with methods that rely on full-model tuning.
