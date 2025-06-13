---
layout: publication
title: 'BREEN: Bridge Data-efficient Encoder-free Multimodal Learning With Learnable Queries'
authors: Tianle Li, Yongming Rao, Winston Hu, Yu Cheng
conference: "Arxiv"
year: 2025
bibkey: li2025bridge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.12446"}
tags: ['Efficiency and Optimization', 'RAG', 'Model Architecture', 'Training Techniques', 'Multimodal Models']
---
Encoder-free multimodal large language models(MLLMs) eliminate the need for a
well-trained vision encoder by directly processing image tokens before the
language model. While this approach reduces computational overhead and model
complexity, it often requires large amounts of training data to effectively
capture the visual knowledge typically encoded by vision models like CLIP. The
absence of a vision encoder implies that the model is likely to rely on
substantial data to learn the necessary visual-semantic alignments. In this
work, we present BREEN, a data-efficient encoder-free multimodal architecture
that mitigates this issue. BREEN leverages a learnable query and image experts
to achieve comparable performance with significantly less training data. The
learnable query, positioned between image and text tokens, is supervised by the
output of a pretrained CLIP model to distill visual knowledge, bridging the gap
between visual and textual modalities. Additionally, the image expert processes
image tokens and learnable queries independently, improving efficiency and
reducing interference with the LLM's textual capabilities. BREEN achieves
comparable performance to prior encoder-free state-of-the-art models like
Mono-InternVL, using only 13 million text-image pairs in training about one
percent of the data required by existing methods. Our work highlights a
promising direction for data-efficient encoder-free multimodal learning,
offering an alternative to traditional encoder-based approaches.
