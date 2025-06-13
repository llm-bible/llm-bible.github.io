---
layout: publication
title: 'Chrono: A Simple Blueprint For Representing Time In Mllms'
authors: Boris Meinardus, Hector Rodriguez, Anil Batra, Anna Rohrbach, Marcus Rohrbach
conference: "Arxiv"
year: 2024
bibkey: meinardus2024simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18113"}
tags: ['Multimodal Models', 'Model Architecture', 'RAG', 'Prompting', 'Applications']
---
The recent success of Large Language Models (LLMs) has prompted the extension
to the multimodal domain developing image-text Multimodal LLMs (MLLMs) and then
video-text models. In this work, we investigate the challenge of contextual and
temporal comprehension in video-language models by exploring the task of
temporal localization in videos. To address this problem, prior works have
developed complex task-specific architectures, novel modules to embed time into
MLLMs, or leveraged additional input signals such as video transcripts to best
encode contextual and temporal information. Interestingly, we find that most of
these efforts are surpassed by a much simpler design. We introduce Chrono, a
universal sequence blueprint that can be applied to an image-text pretrained
MLLM. Through extensive ablations across different MLLM architectures,
finetuning and zero-shot settings, and different datasets, we achieve a new
SOTA in moment retrieval on the most widely used benchmarks Charades-STA,
QVHighlights, ActivityNet Captions, and grounded video question answering on
NeXT-GQA.
