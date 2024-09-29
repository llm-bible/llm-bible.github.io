---
layout: publication
title: Enhancing Black45;box Few45;shot Text Classification With Prompt45;based Data Augmentation
authors: Luo Danqing, Zhang Chen, Xu Jiahui, Wang Bin, Chen Yiming, Zhang Yan, Li Haizhou
conference: "Arxiv"
year: 2023
bibkey: luo2023enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.13785"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Tools', 'Training Techniques']
---
Training or finetuning large45;scale language models (LLMs) such as GPT45;3 requires substantial computation resources motivating recent efforts to explore parameter45;efficient adaptation to downstream tasks. One practical area of research is to treat these models as black boxes and interact with them through their inference APIs. In this paper we investigate how to optimize few45;shot text classification without accessing the gradients of the LLMs. To achieve this we treat the black45;box model as a feature extractor and train a classifier with the augmented text data. Data augmentation is performed using prompt45;based finetuning on an auxiliary language model with a much smaller parameter size than the black45;box model. Through extensive experiments on eight text classification datasets we show that our approach dubbed BT45;Classifier significantly outperforms state45;of45;the45;art black45;box few45;shot learners and performs on par with methods that rely on full45;model tuning.
