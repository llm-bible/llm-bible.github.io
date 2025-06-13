---
layout: publication
title: 'Scenecraft: An LLM Agent For Synthesizing 3D Scene As Blender Code'
authors: Ziniu Hu, Ahmet Iscen, Aashi Jain, Thomas Kipf, Yisong Yue, David A. Ross, Cordelia Schmid, Alireza Fathi
conference: "Arxiv"
year: 2024
bibkey: hu2024llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.01248"}
tags: ['Agentic', 'GPT', 'Tools', 'RAG', 'Model Architecture', 'Multimodal Models']
---
This paper introduces SceneCraft, a Large Language Model (LLM) Agent
converting text descriptions into Blender-executable Python scripts which
render complex scenes with up to a hundred 3D assets. This process requires
complex spatial planning and arrangement. We tackle these challenges through a
combination of advanced abstraction, strategic planning, and library learning.
SceneCraft first models a scene graph as a blueprint, detailing the spatial
relationships among assets in the scene. SceneCraft then writes Python scripts
based on this graph, translating relationships into numerical constraints for
asset layout. Next, SceneCraft leverages the perceptual strengths of
vision-language foundation models like GPT-V to analyze rendered images and
iteratively refine the scene. On top of this process, SceneCraft features a
library learning mechanism that compiles common script functions into a
reusable library, facilitating continuous self-improvement without expensive
LLM parameter tuning. Our evaluation demonstrates that SceneCraft surpasses
existing LLM-based agents in rendering complex scenes, as shown by its
adherence to constraints and favorable human assessments. We also showcase the
broader application potential of SceneCraft by reconstructing detailed 3D
scenes from the Sintel movie and guiding a video generative model with
generated scenes as intermediary control signal.
