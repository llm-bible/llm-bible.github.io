---
layout: publication
title: 'Escaping The Sentence-level Paradigm In Machine Translation'
authors: Matt Post, Marcin Junczys-dowmunt
conference: "Arxiv"
year: 2023
bibkey: post2023escaping
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2304.12959"}
tags: ['Training Techniques', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Transformer', 'Applications']
---
It is well-known that document context is vital for resolving a range of
translation ambiguities, and in fact the document setting is the most natural
setting for nearly all translation. It is therefore unfortunate that machine
translation -- both research and production -- largely remains stuck in a
decades-old sentence-level translation paradigm. It is also an increasingly
glaring problem in light of competitive pressure from large language models,
which are natively document-based. Much work in document-context machine
translation exists, but for various reasons has been unable to catch hold. This
paper suggests a path out of this rut by addressing three impediments at once:
what architectures should we use? where do we get document-level information
for training them? and how do we know whether they are any good? In contrast to
work on specialized architectures, we show that the standard Transformer
architecture is sufficient, provided it has enough capacity. Next, we address
the training data issue by taking document samples from back-translated data
only, where the data is not only more readily available, but is also of higher
quality compared to parallel document data, which may contain machine
translation output. Finally, we propose generative variants of existing
contrastive metrics that are better able to discriminate among document
systems. Results in four large-data language pairs (DE\\(\rightarrow\\)EN,
EN\\(\rightarrow\\)DE, EN\\(\rightarrow\\)FR, and EN\\(\rightarrow\\)RU) establish the
success of these three pieces together in improving document-level performance.
