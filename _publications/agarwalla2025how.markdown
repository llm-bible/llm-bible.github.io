---
layout: publication
title: 'Nanovlms: How Small Can We Go And Still Make Coherent Vision Language Models?'
authors: Mukund Agarwalla, Himanshu Kumar, Raj Dandekar, Rajat Dandekar, Sreedath Panat
conference: "Arxiv"
year: 2025
bibkey: agarwalla2025how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.07838"}
tags: ['GPT', 'RAG', 'Model Architecture', 'Training Techniques', 'Attention Mechanism', 'Multimodal Models']
---
Vision-Language Models (VLMs), such as GPT-4V and Llama 3.2 vision, have
garnered significant research attention for their ability to leverage Large
Language Models (LLMs) in multimodal tasks. However, their potential is
constrained by inherent challenges, including proprietary restrictions,
substantial computational demands, and limited accessibility. Smaller models,
such as GIT and BLIP, exhibit marked limitations, often failing to generate
coherent and consistent text beyond a few tokens, even with extensive training.
This underscores a pivotal inquiry: how small can a VLM be and still produce
fluent and consistent text? Drawing inspiration from the exceptional learning
process of 3-4 year old children, who rely heavily on visual cues for
understanding and communication, we introduce two novel datasets: ShortDesc
(featuring concise image descriptions) and LongDesc (containing more detailed
image descriptions). These datasets consist of image-text pairs where the text
is restricted to the simple vocabulary and syntax typically used by young
children, generated with a scaled-down model, GPT-4o. Using these datasets, we
demonstrate that it is possible to train VLMs that are significantly smaller,
up to 10 times smaller than state of the art(SOTA) small VLMs while maintaining
architectural simplicity. To evaluate the outputs, we leverage GPT-4o to grade
the text, as if stories written by students, on creativity, meaningfulness, and
consistency, assigning scores out of 10. This method addresses limitations of
standard benchmarks by accommodating unstructured outputs and providing a
multidimensional evaluation of the model capabilities. Our findings contribute
to the development of lightweight, accessible multimodal models for resource
constrained environments.
