---
layout: publication
title: 'Divide And Conquer: Language Models Can Plan And Self-correct For Compositional Text-to-image Generation'
authors: Zhenyu Wang, Enze Xie, Aoxue Li, Zhongdao Wang, Xihui Liu, Zhenguo Li
conference: "Arxiv"
year: 2024
bibkey: wang2024divide
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.15688"}
tags: ['Agentic', 'Tools', 'Applications', 'Reinforcement Learning', 'Merging', 'Training Techniques', 'Prompting']
---
Despite significant advancements in text-to-image models for generating
high-quality images, these methods still struggle to ensure the controllability
of text prompts over images in the context of complex text prompts, especially
when it comes to retaining object attributes and relationships. In this paper,
we propose CompAgent, a training-free approach for compositional text-to-image
generation, with a large language model (LLM) agent as its core. The
fundamental idea underlying CompAgent is premised on a divide-and-conquer
methodology. Given a complex text prompt containing multiple concepts including
objects, attributes, and relationships, the LLM agent initially decomposes it,
which entails the extraction of individual objects, their associated
attributes, and the prediction of a coherent scene layout. These individual
objects can then be independently conquered. Subsequently, the agent performs
reasoning by analyzing the text, plans and employs the tools to compose these
isolated objects. The verification and human feedback mechanism is finally
incorporated into our agent to further correct the potential attribute errors
and refine the generated images. Guided by the LLM agent, we propose a
tuning-free multi-concept customization model and a layout-to-image generation
model as the tools for concept composition, and a local image editing method as
the tool to interact with the agent for verification. The scene layout controls
the image generation process among these tools to prevent confusion among
multiple objects. Extensive experiments demonstrate the superiority of our
approach for compositional text-to-image generation: CompAgent achieves more
than 10% improvement on T2I-CompBench, a comprehensive benchmark for
open-world compositional T2I generation. The extension to various related tasks
also illustrates the flexibility of our CompAgent for potential applications.
