---
layout: publication
title: Parameter-efficient Tuning Makes A Good Classification Head
authors: Yang Zhuoyi, Ding Ming, Guo Yanhui, Lv Qingsong, Tang Jie
conference: "Arxiv"
year: 2022
bibkey: yang2022parameter
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.16771"}
tags: ['Applications', 'BERT', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
In recent years pretrained models revolutionized the paradigm of natural language understanding (NLU) where we append a randomly initialized classification head after the pretrained backbone e.g. BERT and finetune the whole model. As the pretrained backbone makes a major contribution to the improvement we naturally expect a good pretrained classification head can also benefit the training. However the final-layer output of the backbone i.e. the input of the classification head will change greatly during finetuning making the usual head-only pretraining (LP-FT) ineffective. In this paper we find that parameter-efficient tuning makes a good classification head with which we can simply replace the randomly initialized heads for a stable performance gain. Our experiments demonstrate that the classification head jointly pretrained with parameter-efficient tuning consistently improves the performance on 9 tasks in GLUE and SuperGLUE.
