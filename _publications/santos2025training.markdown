---
layout: publication
title: '\(\infty\)-video: A Training-free Approach To Long Video Understanding Via Continuous-time Memory Consolidation'
authors: Saul Santos, António Farinhas, Daniel C. Mcnamee, André F. T. Martins
conference: "Arxiv"
year: 2025
bibkey: santos2025training
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.19098"}
tags: ['Training Techniques', 'Tools', 'Attention Mechanism', 'Model Architecture']
---
Current video-language models struggle with long-video understanding due to limited context lengths and reliance on sparse frame subsampling, often leading to information loss. This paper introduces \\(\infty\\)-Video, which can process arbitrarily long videos through a continuous-time long-term memory (LTM) consolidation mechanism. Our framework augments video Q-formers by allowing them to process unbounded video contexts efficiently and without requiring additional training. Through continuous attention, our approach dynamically allocates higher granularity to the most relevant video segments, forming "sticky" memories that evolve over time. Experiments with Video-LLaMA and VideoChat2 demonstrate improved performance in video question-answering tasks, showcasing the potential of continuous-time LTM mechanisms to enable scalable and training-free comprehension of long videos.
