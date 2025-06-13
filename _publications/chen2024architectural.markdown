---
layout: publication
title: 'APT: Architectural Planning And Text-to-blueprint Construction Using Large Language Models For Open-world Agents'
authors: Jun Yu Chen, Tao Gao
conference: "Arxiv"
year: 2024
bibkey: chen2024architectural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.17255"}
tags: ['Agentic', 'Multimodal Models', 'Model Architecture', 'Agent', 'Few-Shot', 'Tools', 'Reinforcement Learning', 'RAG', 'Merging', 'GPT']
---
We present APT, an advanced Large Language Model (LLM)-driven framework that
enables autonomous agents to construct complex and creative structures within
the Minecraft environment. Unlike previous approaches that primarily
concentrate on skill-based open-world tasks or rely on image-based diffusion
models for generating voxel-based structures, our method leverages the
intrinsic spatial reasoning capabilities of LLMs. By employing chain-of-thought
decomposition along with multimodal inputs, the framework generates detailed
architectural layouts and blueprints that the agent can execute under zero-shot
or few-shot learning scenarios. Our agent incorporates both memory and
reflection modules to facilitate lifelong learning, adaptive refinement, and
error correction throughout the building process. To rigorously evaluate the
agent's performance in this emerging research area, we introduce a
comprehensive benchmark consisting of diverse construction tasks designed to
test creativity, spatial reasoning, adherence to in-game rules, and the
effective integration of multimodal instructions. Experimental results using
various GPT-based LLM backends and agent configurations demonstrate the agent's
capacity to accurately interpret extensive instructions involving numerous
items, their positions, and orientations. The agent successfully produces
complex structures complete with internal functionalities such as
Redstone-powered systems. A/B testing indicates that the inclusion of a memory
module leads to a significant increase in performance, emphasizing its role in
enabling continuous learning and the reuse of accumulated experience.
Additionally, the agent's unexpected emergence of scaffolding behavior
highlights the potential of future LLM-driven agents to utilize subroutine
planning and leverage the emergence ability of LLMs to autonomously develop
human-like problem-solving techniques.
