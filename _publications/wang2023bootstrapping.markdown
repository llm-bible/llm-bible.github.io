---
layout: publication
title: 'BLSP: Bootstrapping Language-speech Pre-training Via Behavior Alignment Of Continuation Writing'
authors: Chen Wang, Minpeng Liao, Zhongqiang Huang, Jinliang Lu, Junhong Wu, Yuchen Liu, Chengqing Zong, Jiajun Zhang
conference: "Arxiv"
year: 2023
bibkey: wang2023bootstrapping
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.00916'}
tags: ['Prompting', 'INTERSPEECH', 'Training Techniques', 'Pre-Training']
---
The emergence of large language models (LLMs) has sparked significant
interest in extending their remarkable language capabilities to speech.
However, modality alignment between speech and text still remains an open
problem. Current solutions can be categorized into two strategies. One is a
cascaded approach where outputs (tokens or states) of a separately trained
speech recognition system are used as inputs for LLMs, which limits their
potential in modeling alignment between speech and text. The other is an
end-to-end approach that relies on speech instruction data, which is very
difficult to collect in large quantities. In this paper, we address these
issues and propose the BLSP approach that Bootstraps Language-Speech
Pre-training via behavior alignment of continuation writing. We achieve this by
learning a lightweight modality adapter between a frozen speech encoder and an
LLM, ensuring that the LLM exhibits the same generation behavior regardless of
the modality of input: a speech segment or its transcript. The training process
can be divided into two steps. The first step prompts an LLM to generate texts
with speech transcripts as prefixes, obtaining text continuations. In the
second step, these continuations are used as supervised signals to train the
modality adapter in an end-to-end manner. We demonstrate that this
straightforward process can extend the capabilities of LLMs to speech, enabling
speech recognition, speech translation, spoken language understanding, and
speech conversation, even in zero-shot cross-lingual scenarios.
