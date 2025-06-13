---
layout: publication
title: 'Videogpt+: Integrating Image And Video Encoders For Enhanced Video Understanding'
authors: Muhammad Maaz, Hanoona Rasheed, Salman Khan, Fahad Khan
conference: "Arxiv"
year: 2024
bibkey: maaz2024integrating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.09418'}
  - {name: "Code", url: 'https://github.com/mbzuai-oryx/VideoGPT-plus'}
tags: ['GPT', 'Has Code', 'Multimodal Models', 'Model Architecture']
---
Building on the advances of language models, Large Multimodal Models (LMMs)
have contributed significant improvements in video understanding. While the
current video LMMs utilize advanced Large Language Models (LLMs), they rely on
either image or video encoders to process visual inputs, each of which has its
own limitations. Image encoders excel at capturing rich spatial details from
frame sequences but lack explicit temporal context, which can be important in
videos with intricate action sequences. On the other hand, video encoders
provide temporal context but are often limited by computational constraints
that lead to processing only sparse frames at lower resolutions, resulting in
reduced contextual and spatial understanding. To this end, we introduce
VideoGPT+, which combines the complementary benefits of the image encoder (for
detailed spatial understanding) and the video encoder (for global temporal
context modeling). The model processes videos by dividing them into smaller
segments and applies an adaptive pooling strategy on features extracted by both
image and video encoders. Our architecture showcases improved performance
across multiple video benchmarks, including VCGBench, MVBench and Zero-shot
question-answering. Further, we develop 112K video-instruction set using a
novel semi-automatic annotation pipeline which further improves the model
performance. Additionally, to comprehensively evaluate video LMMs, we present
VCGBench-Diverse, covering 18 broad video categories such as lifestyle, sports,
science, gaming, and surveillance videos. This benchmark with 4,354
question-answer pairs evaluates the generalization of existing LMMs on dense
video captioning, spatial and temporal understanding, and complex reasoning,
ensuring comprehensive assessment across diverse video types and dynamics.
Code: https://github.com/mbzuai-oryx/VideoGPT-plus.
