---
layout: publication
title: 'Vision And Intention Boost Large Language Model In Long-term Action Anticipation'
authors: Congqi Cao, Lanshu Hu, Yating Yu, Yanning Zhang
conference: "Arxiv"
year: 2025
bibkey: cao2025vision
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.01713'}
tags: ['RAG', 'Merging', 'Prompting', 'Multimodal Models', 'In-Context Learning']
---
Long-term action anticipation (LTA) aims to predict future actions over an
extended period. Previous approaches primarily focus on learning exclusively
from video data but lack prior knowledge. Recent researches leverage large
language models (LLMs) by utilizing text-based inputs which suffer severe
information loss. To tackle these limitations single-modality methods face, we
propose a novel Intention-Conditioned Vision-Language (ICVL) model in this
study that fully leverages the rich semantic information of visual data and the
powerful reasoning capabilities of LLMs. Considering intention as a high-level
concept guiding the evolution of actions, we first propose to employ a
vision-language model (VLM) to infer behavioral intentions as comprehensive
textual features directly from video inputs. The inferred intentions are then
fused with visual features through a multi-modality fusion strategy, resulting
in intention-enhanced visual representations. These enhanced visual
representations, along with textual prompts, are fed into LLM for future action
anticipation. Furthermore, we propose an effective example selection strategy
jointly considers visual and textual similarities, providing more relevant and
informative examples for in-context learning. Extensive experiments with
state-of-the-art performance on Ego4D, EPIC-Kitchens-55, and EGTEA GAZE+
datasets fully demonstrate the effectiveness and superiority of the proposed
method.
