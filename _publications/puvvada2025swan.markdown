---
layout: publication
title: 'SWAN-GPT: An Efficient And Scalable Approach For Long-context Language Modeling'
authors: Krishna C. Puvvada, Faisal Ladhak, Santiago Akle Serrano, Cheng-ping Hsieh, Shantanu Acharya, Somshubra Majumdar, Fei Jia, Samuel Kriman, Simeng Sun, Dima Rekesh, Boris Ginsburg
conference: "Arxiv"
year: 2025
bibkey: puvvada2025swan
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.08719'}
tags: ['Attention Mechanism', 'Language Modeling', 'Transformer', 'GPT', 'Training Techniques', 'Model Architecture', 'Reinforcement Learning', 'Pretraining Methods']
---
We present a decoder-only Transformer architecture that robustly generalizes
to sequence lengths substantially longer than those seen during training. Our
model, SWAN-GPT, interleaves layers without positional encodings (NoPE) and
sliding-window attention layers equipped with rotary positional encodings
(SWA-RoPE). Experiments demonstrate strong performance on sequence lengths
significantly longer than the training length without the need for additional
long-context training. This robust length extrapolation is achieved through our
novel architecture, enhanced by a straightforward dynamic scaling of attention
scores during inference. In addition, SWAN-GPT is more computationally
efficient than standard GPT architectures, resulting in cheaper training and
higher throughput. Further, we demonstrate that existing pre-trained
decoder-only models can be efficiently converted to the SWAN architecture with
minimal continued training, enabling longer contexts. Overall, our work
presents an effective approach for scaling language models to longer contexts
in a robust and efficient manner.
