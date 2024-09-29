---
layout: publication
title: Moca Incorporating Multi45;stage Domain Pretraining And Cross45;guided Multimodal Attention For Textbook Question Answering
authors: Xu Fangzhi, Lin Qika, Liu Jun, Zhang Lingling, Zhao Tianzhe, Chai Qi, Pan Yudai
conference: "Arxiv"
year: 2021
bibkey: xu2021incorporating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2112.02839"}
tags: ['Applications', 'Attention Mechanism', 'Merging', 'Model Architecture', 'Multimodal Models', 'Pretraining Methods', 'Training Techniques']
---
Textbook Question Answering (TQA) is a complex multimodal task to infer answers given large context descriptions and abundant diagrams. Compared with Visual Question Answering (VQA) TQA contains a large number of uncommon terminologies and various diagram inputs. It brings new challenges to the representation capability of language model for domain45;specific spans. And it also pushes the multimodal fusion to a more complex level. To tackle the above issues we propose a novel model named MoCA which incorporates multi45;stage domain pretraining and multimodal cross attention for the TQA task. Firstly we introduce a multi45;stage domain pretraining module to conduct unsupervised post45;pretraining with the span mask strategy and supervised pre45;finetune. Especially for domain post45;pretraining we propose a heuristic generation algorithm to employ the terminology corpus. Secondly to fully consider the rich inputs of context and diagrams we propose cross45;guided multimodal attention to update the features of text question diagram and instructional diagram based on a progressive strategy. Further a dual gating mechanism is adopted to improve the model ensemble. The experimental results show the superiority of our model which outperforms the state45;of45;the45;art methods by 2.2137; and 2.4337; for validation and test split respectively.
