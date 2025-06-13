---
layout: publication
title: 'Koala: Key Frame-conditioned Long Video-llm'
authors: Reuben Tan, Ximeng Sun, Ping Hu, Jui-hsien Wang, Hanieh Deilamsalehy, Bryan A. Plummer, Bryan Russell, Kate Saenko
conference: "Arxiv"
year: 2024
bibkey: tan2024key
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.04346"}
tags: ['Training Techniques', 'Applications']
---
Long video question answering is a challenging task that involves recognizing
short-term activities and reasoning about their fine-grained relationships.
State-of-the-art video Large Language Models (vLLMs) hold promise as a viable
solution due to their demonstrated emergent capabilities on new tasks. However,
despite being trained on millions of short seconds-long videos, vLLMs are
unable to understand minutes-long videos and accurately answer questions about
them. To address this limitation, we propose a lightweight and self-supervised
approach, Key frame-conditioned long video-LLM (Koala), that introduces
learnable spatiotemporal queries to adapt pretrained vLLMs for generalizing to
longer videos. Our approach introduces two new tokenizers that condition on
visual tokens computed from sparse video key frames for understanding short and
long video moments. We train our proposed approach on HowTo100M and demonstrate
its effectiveness on zero-shot long video understanding benchmarks, where it
outperforms state-of-the-art large models by 3 - 6% in absolute accuracy across
all tasks. Surprisingly, we also empirically show that our approach not only
helps a pretrained vLLM to understand long videos but also improves its
accuracy on short-term action recognition.
