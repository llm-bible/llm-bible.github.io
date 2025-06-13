---
layout: publication
title: 'Reducing Position Bias In Simultaneous Machine Translation With Length-aware Framework'
authors: Shaolei Zhang, Yang Feng
conference: "Arxiv"
year: 2022
bibkey: zhang2022reducing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2203.09053"}
tags: ['Model Architecture', 'Tools', 'Ethics and Bias', 'Applications', 'Attention Mechanism']
---
Simultaneous machine translation (SiMT) starts translating while receiving
the streaming source inputs, and hence the source sentence is always incomplete
during translating. Different from the full-sentence MT using the conventional
seq-to-seq architecture, SiMT often applies prefix-to-prefix architecture,
which forces each target word to only align with a partial source prefix to
adapt to the incomplete source in streaming inputs. However, the source words
in the front positions are always illusoryly considered more important since
they appear in more prefixes, resulting in position bias, which makes the model
pay more attention on the front source positions in testing. In this paper, we
first analyze the phenomenon of position bias in SiMT, and develop a
Length-Aware Framework to reduce the position bias by bridging the structural
gap between SiMT and full-sentence MT. Specifically, given the streaming
inputs, we first predict the full-sentence length and then fill the future
source position with positional encoding, thereby turning the streaming inputs
into a pseudo full-sentence. The proposed framework can be integrated into most
existing SiMT methods to further improve performance. Experiments on two
representative SiMT methods, including the state-of-the-art adaptive policy,
show that our method successfully reduces the position bias and thereby
achieves better SiMT performance.
