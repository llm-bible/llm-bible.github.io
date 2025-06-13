---
layout: publication
title: 'Structural Analysis Of An All-purpose Question Answering Model'
authors: Vincent Micheli, Quentin Heinrich, François Fleuret, Wacim Belblidia
conference: "Arxiv"
year: 2021
bibkey: micheli2021structural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2104.06045"}
tags: ['Model Architecture', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
Attention is a key component of the now ubiquitous pre-trained language
models. By learning to focus on relevant pieces of information, these
Transformer-based architectures have proven capable of tackling several tasks
at once and sometimes even surpass their single-task counterparts. To better
understand this phenomenon, we conduct a structural analysis of a new
all-purpose question answering model that we introduce. Surprisingly, this
model retains single-task performance even in the absence of a strong transfer
effect between tasks. Through attention head importance scoring, we observe
that attention heads specialize in a particular task and that some heads are
more conducive to learning than others in both the multi-task and single-task
settings.
