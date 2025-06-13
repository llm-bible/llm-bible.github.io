---
layout: publication
title: 'Versatilemotion: A Unified Framework For Motion Synthesis And Comprehension'
authors: Zeyu Ling, Bo Han, Shiyang Li, Jikang Cheng, Hongdeng Shen, Changqing Zou
conference: "Arxiv"
year: 2024
bibkey: ling2024unified
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2411.17335'}
tags: ['Agentic', 'Transformer', 'Model Architecture', 'GPT', 'Tools', 'Multimodal Models', 'Reinforcement Learning', 'Pretraining Methods']
---
Large language models (LLMs) are, by design, inherently capable of multi-task learning: through a unified next-token prediction paradigm, they can naturally address a wide variety of downstream tasks. Prior work in the motion domain has demonstrated some generality by adapting LLMs via a Motion Tokenizer coupled with an autoregressive Transformer to generate and understand human motion. However, this generality remains limited in scope and yields only modest performance gains. We introduce VersatileMotion, a unified multimodal motion LLM that combines a novel motion tokenizer, integrating VQ-VAE with flow matching, and an autoregressive transformer backbone to seamlessly support at least nine distinct motion-related tasks. VersatileMotion is the first method to handle single-agent and multi-agent motions in a single framework and enable cross-modal conversion between motion, text, music, and speech, achieving state-of-the-art performance on seven of these tasks. Each sequence in MotionHub may include one or more of the following annotations: natural-language captions, music or audio clips, speech transcripts, and multi-agent interaction data. To facilitate evaluation, we define and release benchmark splits covering nine core tasks. Extensive experiments demonstrate the superior performance, versatility, and potential of VersatileMotion as a foundational model for future understanding and generation of motion.
