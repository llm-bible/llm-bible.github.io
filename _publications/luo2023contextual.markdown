---
layout: publication
title: 'Contextual Knowledge Pursuit For Faithful Visual Synthesis'
authors: Jinqi Luo, Kwan Ho Ryan Chan, Dimitris Dimos, René Vidal
conference: "Arxiv"
year: 2023
bibkey: luo2023contextual
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2311.17898'}
tags: ['Large-Scale Training', 'RAG', 'Training Techniques', 'Tools', 'Fine-Tuning', 'Prompting', 'Reinforcement Learning', 'Pretraining Methods']
---
Modern text-to-vision generative models often hallucinate when the prompt
describing the scene to be generated is underspecified. In large language
models (LLMs), a prevalent strategy to reduce hallucinations is to retrieve
factual knowledge from an external database. While such retrieval augmentation
strategies have great potential to enhance text-to-vision generators, existing
static top-K retrieval methods explore the knowledge pool once, missing the
broader context necessary for high-quality generation. Furthermore, LLMs
internally possess rich world knowledge learned during large-scale training
(parametric knowledge) that could mitigate the need for external data
retrieval. This paper proposes Contextual Knowledge Pursuit (CKPT), a framework
that leverages the complementary strengths of external and parametric knowledge
to help generators produce reliable visual content. Instead of the one-time
retrieval of facts from an external database to improve a given prompt, CKPT
uses (1) an LLM to decide whether to seek external knowledge or to self-elicit
descriptions from LLM parametric knowledge, (2) a knowledge pursuit process to
contextually seek and sequentially gather most relevant facts, (3) a knowledge
aggregator for prompt enhancement with the gathered fact context, and (4) a
filtered fine-tuning objective to improve visual synthesis with richer prompts.
We evaluate CKPT across multiple text-driven generative tasks (image, 3D
rendering, and video) on datasets of rare objects and daily scenarios. Our
results show that CKPT is capable of generating faithful and semantically rich
content across diverse visual domains, offering a promising data source for
zero-shot synthesis and filtered fine-tuning of text-to-vision generative
models.
