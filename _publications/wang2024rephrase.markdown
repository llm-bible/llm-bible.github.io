---
layout: publication
title: 'Rephrase And Contrast: Fine-tuning Language Models For Enhanced Understanding Of Communication And Computer Networks'
authors: Liujianfu Wang, Yuyang Du, Jingqi Lin, Kexin Chen, Soung Chang Liew
conference: "Arxiv"
year: 2024
bibkey: wang2024rephrase
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.19007"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'GPT', 'Ethics and Bias', 'Pretraining Methods', 'KDD', 'Fine-Tuning', 'Prompting']
---
Large language models (LLMs) are being widely researched across various
disciplines, with significant recent efforts focusing on adapting LLMs for
understanding of how communication networks operate. However, over-reliance on
prompting techniques hinders the full exploitation of the generalization
ability of these models, and the lack of efficient fine-tuning methods prevents
the full realization of lightweight LLMs' potential. This paper addresses these
challenges by introducing our Rephrase and Contrast (RaC) framework, an
efficient fine-tuning framework. RaC enhances LLMs' comprehension and critical
thinking abilities by incorporating question reformulation and contrastive
analysis of correct and incorrect answers during the fine-tuning process.
Experimental results demonstrate a 63.73% accuracy improvement over the
foundational model when tested on a comprehensive networking problem set.
Moreover, to efficiently construct the dataset for RaC fine-tuning, we develop
a GPT-assisted data mining method for generating high-quality question-answer
(QA) pairs; furthermore, we introduce ChoiceBoost, a data augmentation
technique that expands dataset size while reducing answer-order bias. Apart
from these technical innovations, we contribute to the networking community by
open-sourcing valuable research resources, including: 1) the fine-tuned
networking model referred to as RaC-Net, 2) the training dataset used for
fine-tuning the model, 3) three testing problem sets of different difficulties
to serve as benchmarks for future research, and 4) code associated with the
above resources.
