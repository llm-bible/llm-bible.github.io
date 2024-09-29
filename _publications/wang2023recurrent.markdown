---
layout: publication
title: READ\: Recurrent Adaptation Of Large Transformers
authors: Wang Sid, Nguyen John, Li Ke, Wu Carole-jean
conference: "Arxiv"
year: 2023
bibkey: wang2023recurrent
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.15348"}
tags: ['Applications', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Fine-tuning large-scale Transformers has led to the explosion of many AI applications across Natural Language Processing and Computer Vision tasks. However fine-tuning all pre-trained model parameters becomes impractical as the model size and number of tasks increase. Parameter-efficient transfer learning (PETL) methods aim to address these challenges. While effective in reducing the number of trainable parameters PETL methods still require significant energy and computational resources to fine-tune. In this paper we introduce (textbfRE)current (textbfAD)aption (READ) -- a lightweight and memory-efficient fine-tuning method -- to overcome the limitations of the current PETL approaches. Specifically READ inserts a small RNN network alongside the backbone model so that the model does not have to back-propagate through the large backbone network. Through comprehensive empirical evaluation of the GLUE benchmark we demonstrate READ can achieve a 5637; reduction in the training memory consumption and an 8437; reduction in the GPU energy usage while retraining high model quality compared to full-tuning. Additionally the model size of READ does not grow with the backbone model size making it a highly scalable solution for fine-tuning large Transformers.
