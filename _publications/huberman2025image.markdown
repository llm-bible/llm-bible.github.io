---
layout: publication
title: 'Image Generation From Contextually-contradictory Prompts'
authors: Saar Huberman, Or Patashnik, Omer Dahary, Ron Mokady, Daniel Cohen-or
conference: "Arxiv"
year: 2025
bibkey: huberman2025image
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.01929"}
tags: ['Tools', 'RAG', 'Merging', 'Training Techniques', 'Prompting']
---
Text-to-image diffusion models excel at generating high-quality, diverse images from natural language prompts. However, they often fail to produce semantically accurate results when the prompt contains concept combinations that contradict their learned priors. We define this failure mode as contextual contradiction, where one concept implicitly negates another due to entangled associations learned during training. To address this, we propose a stage-aware prompt decomposition framework that guides the denoising process using a sequence of proxy prompts. Each proxy prompt is constructed to match the semantic content expected to emerge at a specific stage of denoising, while ensuring contextual coherence. To construct these proxy prompts, we leverage a large language model (LLM) to analyze the target prompt, identify contradictions, and generate alternative expressions that preserve the original intent while resolving contextual conflicts. By aligning prompt information with the denoising progression, our method enables fine-grained semantic control and accurate image generation in the presence of contextual contradictions. Experiments across a variety of challenging prompts show substantial improvements in alignment to the textual prompt.
