---
layout: publication
title: 'On The Interplay Between Fine-tuning And Composition In Transformers'
authors: Yu Lang, Ettinger Allyson
conference: "Arxiv"
year: 2021
bibkey: yu2021interplay
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2105.14668"}
tags: ['Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Transformer']
---
Pre-trained transformer language models have shown remarkable performance on
a variety of NLP tasks. However, recent research has suggested that
phrase-level representations in these models reflect heavy influences of
lexical content, but lack evidence of sophisticated, compositional phrase
information. Here we investigate the impact of fine-tuning on the capacity of
contextualized embeddings to capture phrase meaning information beyond lexical
content. Specifically, we fine-tune models on an adversarial paraphrase
classification task with high lexical overlap, and on a sentiment
classification task. After fine-tuning, we analyze phrasal representations in
controlled settings following prior work. We find that fine-tuning largely
fails to benefit compositionality in these representations, though training on
sentiment yields a small, localized benefit for certain models. In follow-up
analyses, we identify confounding cues in the paraphrase dataset that may
explain the lack of composition benefits from that task, and we discuss
potential factors underlying the localized benefits from sentiment training.
