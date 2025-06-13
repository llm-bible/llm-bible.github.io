---
layout: publication
title: 'Learning To Generate One-sentence Biographies From Wikidata'
authors: Andrew Chisholm, Will Radford, Ben Hachey
conference: "Arxiv"
year: 2017
bibkey: chisholm2017learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/1702.06235'}
tags: ['Reinforcement Learning', 'Attention Mechanism', 'Model Architecture']
---
We investigate the generation of one-sentence Wikipedia biographies from
facts derived from Wikidata slot-value pairs. We train a recurrent neural
network sequence-to-sequence model with attention to select facts and generate
textual summaries. Our model incorporates a novel secondary objective that
helps ensure it generates sentences that contain the input facts. The model
achieves a BLEU score of 41, improving significantly upon the vanilla
sequence-to-sequence model and scoring roughly twice that of a simple template
baseline. Human preference evaluation suggests the model is nearly as good as
the Wikipedia reference. Manual analysis explores content selection, suggesting
the model can trade the ability to infer knowledge against the risk of
hallucinating incorrect information.
