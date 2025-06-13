---
layout: publication
title: 'Probing For Incremental Parse States In Autoregressive Language Models'
authors: Tiwalayo Eisape, Vineet Gangireddy, Roger P. Levy, Yoon Kim
conference: "Arxiv"
year: 2022
bibkey: eisape2022probing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2211.09748'}
tags: ['Reinforcement Learning', 'GPT', 'Pretraining Methods']
---
Next-word predictions from autoregressive neural language models show
remarkable sensitivity to syntax. This work evaluates the extent to which this
behavior arises as a result of a learned ability to maintain implicit
representations of incremental syntactic structures. We extend work in
syntactic probing to the incremental setting and present several probes for
extracting incomplete syntactic structure (operationalized through parse states
from a stack-based parser) from autoregressive language models. We find that
our probes can be used to predict model preferences on ambiguous sentence
prefixes and causally intervene on model representations and steer model
behavior. This suggests implicit incremental syntactic inferences underlie
next-word predictions in autoregressive neural language models.
