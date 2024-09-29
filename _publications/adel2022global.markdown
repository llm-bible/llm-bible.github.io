---
layout: publication
title: Global Memory Transformer For Processing Long Documents
authors: Adel Arij Al
conference: "Arxiv"
year: 2022
bibkey: adel2022global
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2212.01650"}
tags: ['Applications', 'BERT', 'Language Modeling', 'Masked Language Model', 'Model Architecture', 'Pretraining Methods', 'Training Techniques', 'Transformer']
---
Transformer variants dominate the state-of-the-art in different natural language processing tasks such as translation reading comprehension and summarization. Our paper is more directed to use general memory slots added to the inputs and studying the results of adding these slots. This paper is a go on study of general memory slots rule that were added to the input of the proposed model in previous work. We have two main tasks;1) pretraining task using masked language modeling and b) fine tuning task using HotpotQA . This study aims to verify the ability of the proposed model to handle chunks as if they were one chunk comparing with the base model. As baseline we used T5 transformer. We studied the rule of memory slots augmented to each input chunk and studied the model performance without selector. We found that adding memory to input chunks helped the proposed model to overcome the baseline on Masked language modeling task with specific training parameters. Ablation study reveals the ability of using the compressed input chunks with a degradation in performance.
