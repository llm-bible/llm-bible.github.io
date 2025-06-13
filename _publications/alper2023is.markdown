---
layout: publication
title: 'Is BERT Blind? Exploring The Effect Of Vision-and-language Pretraining On Visual Language Understanding'
authors: Morris Alper, Michael Fiman, Hadar Averbuch-elor
conference: "Arxiv"
year: 2023
bibkey: alper2023is
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2303.12513"}
tags: ['Applications', 'Model Architecture', 'Masked Language Model', 'Training Techniques', 'Pretraining Methods', 'BERT', 'Multimodal Models']
---
Most humans use visual imagination to understand and reason about language,
but models such as BERT reason about language using knowledge acquired during
text-only pretraining. In this work, we investigate whether vision-and-language
pretraining can improve performance on text-only tasks that involve implicit
visual reasoning, focusing primarily on zero-shot probing methods. We propose a
suite of visual language understanding (VLU) tasks for probing the visual
reasoning abilities of text encoder models, as well as various non-visual
natural language understanding (NLU) tasks for comparison. We also contribute a
novel zero-shot knowledge probing method, Stroop probing, for applying models
such as CLIP to text-only tasks without needing a prediction head such as the
masked language modelling head of models like BERT. We show that SOTA
multimodally trained text encoders outperform unimodally trained text encoders
on the VLU tasks while being underperformed by them on the NLU tasks, lending
new context to previously mixed results regarding the NLU capabilities of
multimodal models. We conclude that exposure to images during pretraining
affords inherent visual reasoning knowledge that is reflected in language-only
tasks that require implicit visual reasoning. Our findings bear importance in
the broader context of multimodal learning, providing principled guidelines for
the choice of text encoders used in such contexts.
