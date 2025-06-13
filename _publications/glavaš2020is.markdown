---
layout: publication
title: 'Is Supervised Syntactic Parsing Beneficial For Language Understanding? An Empirical Investigation'
authors: Goran Glavaš, Ivan Vulić
conference: "Arxiv"
year: 2020
bibkey: glavaš2020is
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2008.06788'}
tags: ['Language Modeling', 'Transformer', 'Training Techniques', 'Model Architecture', 'Fine-Tuning', 'Pretraining Methods']
---
Traditional NLP has long held (supervised) syntactic parsing necessary for
successful higher-level semantic language understanding (LU). The recent advent
of end-to-end neural models, self-supervised via language modeling (LM), and
their success on a wide range of LU tasks, however, questions this belief. In
this work, we empirically investigate the usefulness of supervised parsing for
semantic LU in the context of LM-pretrained transformer networks. Relying on
the established fine-tuning paradigm, we first couple a pretrained transformer
with a biaffine parsing head, aiming to infuse explicit syntactic knowledge
from Universal Dependencies treebanks into the transformer. We then fine-tune
the model for LU tasks and measure the effect of the intermediate parsing
training (IPT) on downstream LU task performance. Results from both monolingual
English and zero-shot language transfer experiments (with intermediate
target-language parsing) show that explicit formalized syntax, injected into
transformers through IPT, has very limited and inconsistent effect on
downstream LU performance. Our results, coupled with our analysis of
transformers' representation spaces before and after intermediate parsing, make
a significant step towards providing answers to an essential question: how
(un)availing is supervised parsing for high-level semantic natural language
understanding in the era of large neural models?
