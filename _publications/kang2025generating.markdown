---
layout: publication
title: 'Action2dialogue: Generating Character-centric Narratives From Scene-level Prompts'
authors: Taewon Kang, Ming C. Lin
conference: "Arxiv"
year: 2025
bibkey: kang2025generating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.16819'}
tags: ['Prompting', 'Multimodal Models', 'Training Techniques', 'Tools']
---
Recent advances in scene-based video generation have enabled systems to synthesize coherent visual narratives from structured prompts. However, a crucial dimension of storytelling -- character-driven dialogue and speech -- remains underexplored. In this paper, we present a modular pipeline that transforms action-level prompts into visually and auditorily grounded narrative dialogue, enriching visual storytelling with natural voice and character expression. Our method takes as input a pair of prompts per scene, where the first defines the setting and the second specifies a character's behavior. While a story generation model such as Text2Story generates the corresponding visual scene, we focus on generating expressive character utterances from these prompts and the scene image. We apply a pretrained vision-language encoder to extract a high-level semantic feature from the representative frame, capturing salient visual context. This feature is then combined with the structured prompts and used to guide a large language model in synthesizing natural, character-consistent dialogue. To ensure contextual consistency across scenes, we introduce a Recursive Narrative Bank that conditions each dialogue generation on the accumulated dialogue history from prior scenes. This approach enables characters to speak in ways that reflect their evolving goals and interactions throughout a story. Finally, we render each utterance as expressive, character-consistent speech, resulting in fully-voiced video narratives. Our framework requires no additional training and demonstrates applicability across a variety of story settings, from fantasy adventures to slice-of-life episodes.
