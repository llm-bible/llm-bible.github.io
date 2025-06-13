---
layout: publication
title: 'Iqvic: In-context, Question Adaptive Vision Compressor For Long-term Video Understanding Lmms'
authors: Sosuke Yamao, Natsuki Miyahara, Yuki Harazono, Shun Takeuchi
conference: "Arxiv"
year: 2024
bibkey: yamao2024question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.09907"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Tools', 'Pretraining Methods', 'Transformer', 'Applications', 'Attention Mechanism']
---
With the increasing complexity of video data and the need for more efficient
long-term temporal understanding, existing long-term video understanding
methods often fail to accurately capture and analyze extended video sequences.
These methods typically struggle to maintain performance over longer durations
and to handle the intricate dependencies within the video content. To address
these limitations, we propose a simple yet effective large multi-modal model
framework for long-term video understanding that incorporates a novel visual
compressor, the In-context, Question Adaptive Visual Compressor (IQViC). The
key idea, inspired by humans' selective attention and in-context memory
mechanisms, is to introduce a novel visual compressor and incorporate efficient
memory management techniques to enhance long-term video question answering. Our
framework utilizes IQViC, a transformer-based visual compressor, enabling
question-conditioned in-context compression, unlike existing methods that rely
on full video visual features. This selectively extracts relevant information,
significantly reducing memory token requirements. Through extensive experiments
on a new dataset based on InfiniBench for long-term video understanding, and
standard benchmarks used for existing methods' evaluation, we demonstrate the
effectiveness of our proposed IQViC framework and its superiority over
state-of-the-art methods in terms of video understanding accuracy and memory
efficiency.
