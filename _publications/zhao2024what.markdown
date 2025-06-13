---
layout: publication
title: 'What Matters In Memorizing And Recalling Facts? Multifaceted Benchmarks For Knowledge Probing In Language Models'
authors: Xin Zhao, Naoki Yoshinaga, Daisuke Oba
conference: "Arxiv"
year: 2024
bibkey: zhao2024what
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.12277"}
tags: ['Training Techniques', 'Pretraining Methods', 'Fine-Tuning', 'Prompting', 'In-Context Learning']
---
Language models often struggle with handling factual knowledge, exhibiting
factual hallucination issue. This makes it vital to evaluate the models'
ability to recall its parametric knowledge about facts. In this study, we
introduce a knowledge probing benchmark, BELIEF(ICL), to evaluate the knowledge
recall ability of both encoder- and decoder-based pre-trained language models
(PLMs) from diverse perspectives. BELIEFs utilize a multi-prompt dataset to
evaluate PLM's accuracy, consistency, and reliability in factual knowledge
recall. To enable a more reliable evaluation with BELIEFs, we
semi-automatically create MyriadLAMA, which has massively diverse prompts. We
validate the effectiveness of BELIEFs in comprehensively evaluating PLM's
knowledge recall ability on diverse PLMs, including recent large language
models (LLMs). We then investigate key factors in memorizing and recalling
facts in PLMs, such as model size, pretraining strategy and corpora,
instruction-tuning process and in-context learning settings. Finally, we reveal
the limitation of the prompt-based knowledge probing. The MyriadLAMA is
publicized.
