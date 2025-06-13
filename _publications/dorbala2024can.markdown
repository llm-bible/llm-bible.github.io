---
layout: publication
title: 'Can Llms Generate Human-like Wayfinding Instructions? Towards Platform-agnostic Embodied Instruction Synthesis'
authors: Vishnu Sashank Dorbala, Sanjoy Chowdhury, Dinesh Manocha
conference: "Arxiv"
year: 2024
bibkey: dorbala2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11487"}
tags: ['Agentic', 'Tools', 'Applications', 'Reinforcement Learning', 'Training Techniques', 'Prompting', 'In-Context Learning']
---
We present a novel approach to automatically synthesize "wayfinding
instructions" for an embodied robot agent. In contrast to prior approaches that
are heavily reliant on human-annotated datasets designed exclusively for
specific simulation platforms, our algorithm uses in-context learning to
condition an LLM to generate instructions using just a few references. Using an
LLM-based Visual Question Answering strategy, we gather detailed information
about the environment which is used by the LLM for instruction synthesis. We
implement our approach on multiple simulation platforms including Matterport3D,
AI Habitat and ThreeDWorld, thereby demonstrating its platform-agnostic nature.
We subjectively evaluate our approach via a user study and observe that 83.3%
of users find the synthesized instructions accurately capture the details of
the environment and show characteristics similar to those of human-generated
instructions. Further, we conduct zero-shot navigation with multiple approaches
on the REVERIE dataset using the generated instructions, and observe very close
correlation with the baseline on standard success metrics (< 1% change in SR),
quantifying the viability of generated instructions in replacing
human-annotated data. We finally discuss the applicability of our approach in
enabling a generalizable evaluation of embodied navigation policies. To the
best of our knowledge, ours is the first LLM-driven approach capable of
generating "human-like" instructions in a platform-agnostic manner, without
training.
