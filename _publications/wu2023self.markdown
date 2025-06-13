---
layout: publication
title: 'Self-correcting Llm-controlled Diffusion Models'
authors: Tsung-han Wu, Long Lian, Joseph E. Gonzalez, Boyi Li, Trevor Darrell
conference: "Arxiv"
year: 2023
bibkey: wu2023self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.16090"}
tags: ['Tools', 'Applications', 'Merging', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
Text-to-image generation has witnessed significant progress with the advent
of diffusion models. Despite the ability to generate photorealistic images,
current text-to-image diffusion models still often struggle to accurately
interpret and follow complex input text prompts. In contrast to existing models
that aim to generate images only with their best effort, we introduce
Self-correcting LLM-controlled Diffusion (SLD). SLD is a framework that
generates an image from the input prompt, assesses its alignment with the
prompt, and performs self-corrections on the inaccuracies in the generated
image. Steered by an LLM controller, SLD turns text-to-image generation into an
iterative closed-loop process, ensuring correctness in the resulting image. SLD
is not only training-free but can also be seamlessly integrated with diffusion
models behind API access, such as DALL-E 3, to further boost the performance of
state-of-the-art diffusion models. Experimental results show that our approach
can rectify a majority of incorrect generations, particularly in generative
numeracy, attribute binding, and spatial relationships. Furthermore, by simply
adjusting the instructions to the LLM, SLD can perform image editing tasks,
bridging the gap between text-to-image generation and image editing pipelines.
We will make our code available for future research and applications.
