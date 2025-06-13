---
layout: publication
title: 'Musilingo: Bridging Music And Text With Pre-trained Language Models For Music Captioning And Query Response'
authors: Zihao Deng, Yinghao Ma, Yudong Liu, Rongchen Guo, Ge Zhang, Wenhu Chen, Wenhao Huang, Emmanouil Benetos
conference: "2024 Annual Conference of the North American Chapter of the Association for Computational Linguistics"
year: 2023
bibkey: deng2023bridging
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.08730'}
tags: ['Multimodal Models', 'Applications']
---
Large Language Models (LLMs) have shown immense potential in multimodal
applications, yet the convergence of textual and musical domains remains not
well-explored. To address this gap, we present MusiLingo, a novel system for
music caption generation and music-related query responses. MusiLingo employs a
single projection layer to align music representations from the pre-trained
frozen music audio model MERT with a frozen LLM, bridging the gap between music
audio and textual contexts. We train it on an extensive music caption dataset
and fine-tune it with instructional data. Due to the scarcity of high-quality
music Q&A datasets, we created the MusicInstruct (MI) dataset from captions in
the MusicCaps datasets, tailored for open-ended music inquiries. Empirical
evaluations demonstrate its competitive performance in generating music
captions and composing music-related Q&A pairs. Our introduced dataset enables
notable advancements beyond previous ones.
