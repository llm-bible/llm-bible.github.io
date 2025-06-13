---
layout: publication
title: 'Protecting Your Video Content: Disrupting Automated Video-based LLM Annotations'
authors: Haitong Liu, Kuofeng Gao, Yang Bai, Jinmin Li, Jinxiao Shan, Tao Dai, Shu-tao Xia
conference: "Arxiv"
year: 2025
bibkey: liu2025protecting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.21824"}
  - {name: "Code", url: "https://github.com/ttthhl/Protecting_Your_Video_Content"}
tags: ['Security', 'Tools', 'Reinforcement Learning', 'Has Code', 'Prompting']
---
Recently, video-based large language models (video-based LLMs) have achieved
impressive performance across various video comprehension tasks. However, this
rapid advancement raises significant privacy and security concerns,
particularly regarding the unauthorized use of personal video data in automated
annotation by video-based LLMs. These unauthorized annotated video-text pairs
can then be used to improve the performance of downstream tasks, such as
text-to-video generation. To safeguard personal videos from unauthorized use,
we propose two series of protective video watermarks with imperceptible
adversarial perturbations, named Ramblings and Mutes. Concretely, Ramblings aim
to mislead video-based LLMs into generating inaccurate captions for the videos,
thereby degrading the quality of video annotations through inconsistencies
between video content and captions. Mutes, on the other hand, are designed to
prompt video-based LLMs to produce exceptionally brief captions, lacking
descriptive detail. Extensive experiments demonstrate that our video
watermarking methods effectively protect video data by significantly reducing
video annotation performance across various video-based LLMs, showcasing both
stealthiness and robustness in protecting personal video content. Our code is
available at https://github.com/ttthhl/Protecting_Your_Video_Content.
