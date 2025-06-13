---
layout: publication
title: 'How Language Models Prioritize Contextual Grammatical Cues?'
authors: Hamidreza Amirzadeh, Afra Alishahi, Hosein Mohebbi
conference: "Arxiv"
year: 2024
bibkey: amirzadeh2024how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.03447"}
tags: ['Transformer', 'GPT', 'Model Architecture', 'Pretraining Methods', 'BERT']
---
Transformer-based language models have shown an excellent ability to
effectively capture and utilize contextual information. Although various
analysis techniques have been used to quantify and trace the contribution of
single contextual cues to a target task such as subject-verb agreement or
coreference resolution, scenarios in which multiple relevant cues are available
in the context remain underexplored. In this paper, we investigate how language
models handle gender agreement when multiple gender cue words are present, each
capable of independently disambiguating a target gender pronoun. We analyze two
widely used Transformer-based models: BERT, an encoder-based, and GPT-2, a
decoder-based model. Our analysis employs two complementary approaches: context
mixing analysis, which tracks information flow within the model, and a variant
of activation patching, which measures the impact of cues on the model's
prediction. We find that BERT tends to prioritize the first cue in the context
to form both the target word representations and the model's prediction, while
GPT-2 relies more on the final cue. Our findings reveal striking differences in
how encoder-based and decoder-based models prioritize and use contextual
information for their predictions.
