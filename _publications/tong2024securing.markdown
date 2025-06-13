---
layout: publication
title: 'Securing Multi-turn Conversational Language Models From Distributed Backdoor Triggers'
authors: Terry Tong, Jiashu Xu, Qin Liu, Muhao Chen
conference: "Arxiv"
year: 2024
bibkey: tong2024securing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.04151"}
tags: ['RAG', 'Tools', 'Security', 'Reinforcement Learning']
---
Large language models (LLMs) have acquired the ability to handle longer
context lengths and understand nuances in text, expanding their dialogue
capabilities beyond a single utterance. A popular user-facing application of
LLMs is the multi-turn chat setting. Though longer chat memory and better
understanding may seemingly benefit users, our paper exposes a vulnerability
that leverages the multi-turn feature and strong learning ability of LLMs to
harm the end-user: the backdoor. We demonstrate that LLMs can capture the
combinational backdoor representation. Only upon presentation of triggers
together does the backdoor activate. We also verify empirically that this
representation is invariant to the position of the trigger utterance.
Subsequently, inserting a single extra token into two utterances of 5%of the
data can cause over 99% Attack Success Rate (ASR). Our results with 3 triggers
demonstrate that this framework is generalizable, compatible with any trigger
in an adversary's toolbox in a plug-and-play manner. Defending the backdoor can
be challenging in the chat setting because of the large input and output space.
Our analysis indicates that the distributed backdoor exacerbates the current
challenges by polynomially increasing the dimension of the attacked input
space. Canonical textual defenses like ONION and BKI leverage auxiliary model
forward passes over individual tokens, scaling exponentially with the input
sequence length and struggling to maintain computational feasibility. To this
end, we propose a decoding time defense - decayed contrastive decoding - that
scales linearly with assistant response sequence length and reduces the
backdoor to as low as 0.35%.
