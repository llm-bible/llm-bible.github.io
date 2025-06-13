---
layout: publication
title: 'Ladder-of-thought: Using Knowledge As Steps To Elevate Stance Detection'
authors: Kairui Hu, Ming Yan, Joey Tianyi Zhou, Ivor W. Tsang, Wen Haw Chong, Yong Keong Yap
conference: "Arxiv"
year: 2023
bibkey: hu2023ladder
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2308.16763'}
tags: ['Efficiency and Optimization', 'GPT', 'Model Architecture', 'Tools', 'Prompting']
---
Stance detection aims to identify the attitude expressed in a document
towards a given target. Techniques such as Chain-of-Thought (CoT) prompting
have advanced this task, enhancing a model's reasoning capabilities through the
derivation of intermediate rationales. However, CoT relies primarily on a
model's pre-trained internal knowledge during reasoning, thereby neglecting the
valuable external information that is previously unknown to the model. This
omission, especially within the unsupervised reasoning process, can affect the
model's overall performance. Moreover, while CoT enhances Large Language Models
(LLMs), smaller LMs, though efficient operationally, face challenges in
delivering nuanced reasoning. In response to these identified gaps, we
introduce the Ladder-of-Thought (LoT) for the stance detection task.
Constructed through a dual-phase Progressive Optimization Framework, LoT
directs the small LMs to assimilate high-quality external knowledge, refining
the intermediate rationales produced. These bolstered rationales subsequently
serve as the foundation for more precise predictions - akin to how a ladder
facilitates reaching elevated goals. LoT achieves a balance between efficiency
and performance. Our empirical evaluations underscore LoT's efficacy, marking a
16% improvement over GPT-3.5 and a 10% enhancement compared to GPT-3.5 with CoT
on stance detection task.
