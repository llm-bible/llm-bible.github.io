---
layout: publication
title: 'Transfer Learning In Visual And Relational Reasoning'
authors: T. S. Jayram, Vincent Marois, Tomasz Kornuta, Vincent Albouy, Emre Sevgen, Ahmet S. Ozcan
conference: "Arxiv"
year: 2019
bibkey: jayram2019transfer
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1911.11938'}
tags: ['Attention Mechanism', 'Training Techniques', 'Tools', 'Model Architecture', 'Fine-Tuning', 'Applications', 'Pretraining Methods']
---
Transfer learning has become the de facto standard in computer vision and
natural language processing, especially where labeled data is scarce. Accuracy
can be significantly improved by using pre-trained models and subsequent
fine-tuning. In visual reasoning tasks, such as image question answering,
transfer learning is more complex. In addition to transferring the capability
to recognize visual features, we also expect to transfer the system's ability
to reason. Moreover, for video data, temporal reasoning adds another dimension.
In this work, we formalize these unique aspects of transfer learning and
propose a theoretical framework for visual reasoning, exemplified by the
well-established CLEVR and COG datasets. Furthermore, we introduce a new,
end-to-end differentiable recurrent model (SAMNet), which shows
state-of-the-art accuracy and better performance in transfer learning on both
datasets. The improved performance of SAMNet stems from its capability to
decouple the abstract multi-step reasoning from the length of the sequence and
its selective attention enabling to store only the question-relevant objects in
the external memory.
