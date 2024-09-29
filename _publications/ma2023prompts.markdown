---
layout: publication
title: POS&#58; A Prompts Optimization Suite For Augmenting Text-to-video Generation
authors: Ma Shijie, Xu Huayi, Li Mengjian, Geng Weidong, Wang Yaxiong, Wang Meng
conference: "Arxiv"
year: 2023
bibkey: ma2023prompts
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.00949"}
tags: ['Applications', 'Efficiency And Optimization', 'Merging', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
This paper targets to enhance the diffusion-based text-to-video generation by improving the two input prompts including the noise and the text. Accommodated with this goal we propose POS a training-free Prompt Optimization Suite to boost text-to-video models. POS is motivated by two observations (1) Video generation shows instability in terms of noise. Given the same text different noises lead to videos that differ significantly in terms of both frame quality and temporal consistency. This observation implies that there exists an optimal noise matched to each textual input; To capture the potential noise we propose an optimal noise approximator to approach the potential optimal noise. Particularly the optimal noise approximator initially searches a video that closely relates to the text prompt and then inverts it into the noise space to serve as an improved noise prompt for the textual input. (2) Improving the text prompt via LLMs often causes semantic deviation. Many existing text-to-vision works have utilized LLMs to improve the text prompts for generation enhancement. However existing methods often neglect the semantic alignment between the original text and the rewritten one. In response to this issue we design a semantic-preserving rewriter to impose contraints in both rewritng and denoising phrases to preserve the semantic consistency. Extensive experiments on popular benchmarks show that our POS can improve the text-to-video models with a clear margin. The code will be open-sourced.
