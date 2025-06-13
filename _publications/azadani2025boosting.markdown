---
layout: publication
title: 'LEO: Boosting Mixture Of Vision Encoders For Multimodal Large Language Models'
authors: Mozhgan Nasr Azadani, James Riddell, Sean Sedwards, Krzysztof Czarnecki
conference: "Arxiv"
year: 2025
bibkey: azadani2025boosting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.06986"}
tags: ['Tools', 'Model Architecture', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Multimodal Models']
---
Enhanced visual understanding serves as a cornerstone for multimodal large
language models (MLLMs). Recent hybrid MLLMs incorporate a mixture of vision
experts to address the limitations of using a single vision encoder and
excessively long visual tokens. Despite the progress of these MLLMs, a research
gap remains in effectively integrating diverse vision encoders. This work
explores fusion strategies of visual tokens for hybrid MLLMs, leading to the
design of LEO, a novel MLLM with a dual-branch vision encoder framework that
incorporates a post-adaptation fusion strategy and adaptive tiling: for each
segmented tile of the input images, LEO sequentially interleaves the visual
tokens from its two vision encoders. Extensive evaluation across 13
vision-language benchmarks reveals that LEO outperforms state-of-the-art
open-source MLLMs and hybrid MLLMs on the majority of tasks. Furthermore, we
show that LEO can be adapted to the specialized domain of autonomous driving
without altering the model architecture or training recipe, achieving
competitive performance compared to existing baselines. The code and model will
be publicly available.
