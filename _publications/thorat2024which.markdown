---
layout: publication
title: 'Which Llms Are Difficult To Detect? A Detailed Analysis Of Potential Factors Contributing To Difficulties In LLM Text Detection'
authors: Shantanu Thorat, Tianbao Yang
conference: "Arxiv"
year: 2024
bibkey: thorat2024which
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2410.14875'}
tags: ['Training Techniques', 'Tools', 'Model Architecture']
---
As LLMs increase in accessibility, LLM-generated texts have proliferated
across several fields, such as scientific, academic, and creative writing.
However, LLMs are not created equally; they may have different architectures
and training datasets. Thus, some LLMs may be more challenging to detect than
others. Using two datasets spanning four total writing domains, we train
AI-generated (AIG) text classifiers using the LibAUC library - a deep learning
library for training classifiers with imbalanced datasets. Our results in the
Deepfake Text dataset show that AIG-text detection varies across domains, with
scientific writing being relatively challenging. In the Rewritten Ivy Panda
(RIP) dataset focusing on student essays, we find that the OpenAI family of
LLMs was substantially difficult for our classifiers to distinguish from human
texts. Additionally, we explore possible factors that could explain the
difficulties in detecting OpenAI-generated texts.
