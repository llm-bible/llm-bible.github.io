---
layout: publication
title: 'Long Video Understanding With Learnable Retrieval In Video-language Models'
authors: Jiaqi Xu, Cuiling Lan, Wenxuan Xie, Xuejin Chen, Yan Lu
conference: "Arxiv"
year: 2023
bibkey: xu2023long
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.04931"}
tags: ['Training Techniques', 'Applications', 'Tools']
---
The remarkable natural language understanding, reasoning, and generation
capabilities of large language models (LLMs) have made them attractive for
application to video understanding, utilizing video tokens as contextual input.
However, employing LLMs for long video understanding presents significant
challenges. The extensive number of video tokens leads to considerable
computational costs for LLMs while using aggregated tokens results in loss of
vision details. Moreover, the presence of abundant question-irrelevant tokens
introduces noise to the video reasoning process. To address these issues, we
introduce a simple yet effective learnable retrieval-based video-language model
(R-VLM) for efficient long video understanding. Specifically, given a question
(query) and a long video, our model identifies and selects the most relevant K
video chunks and uses their associated visual tokens to serve as context for
the LLM inference. This effectively reduces the number of video tokens,
eliminates noise interference, and enhances system performance. We achieve this
by incorporating a learnable lightweight MLP block to facilitate the efficient
retrieval of question-relevant chunks, through the end-to-end training of our
video-language model with a proposed soft matching loss. Our experimental
results on multiple zero-shot video question answering datasets validate the
effectiveness of our framework for comprehending long videos.
