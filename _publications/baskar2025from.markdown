---
layout: publication
title: 'From Guessing To Asking: An Approach To Resolving The Persona Knowledge Gap In Llms During Multi-turn Conversations'
authors: Sarvesh Baskar, Tanmay Tulsidas Verelakar, Srinivasan Parthasarathy, Manas Gaur
conference: "Arxiv"
year: 2025
bibkey: baskar2025from
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.12556'}
tags: ['Reinforcement Learning', 'Tools']
---
In multi-turn dialogues, large language models (LLM) face a critical
challenge of ensuring coherence while adapting to user-specific information.
This study introduces the persona knowledge gap, the discrepancy between a
model's internal understanding and the knowledge required for coherent,
personalized conversations. While prior research has recognized these gaps,
computational methods for their identification and resolution remain
underexplored. We propose Conversation Preference Elicitation and
Recommendation (CPER), a novel framework that dynamically detects and resolves
persona knowledge gaps using intrinsic uncertainty quantification and
feedback-driven refinement. CPER consists of three key modules: a Contextual
Understanding Module for preference extraction, a Dynamic Feedback Module for
measuring uncertainty and refining persona alignment, and a Persona-Driven
Response Generation module for adapting responses based on accumulated user
context. We evaluate CPER on two real-world datasets: CCPE-M for preferential
movie recommendations and ESConv for mental health support. Using A/B testing,
human evaluators preferred CPER's responses 42% more often than baseline models
in CCPE-M and 27% more often in ESConv. A qualitative human evaluation confirms
that CPER's responses are preferred for maintaining contextual relevance and
coherence, particularly in longer (12+ turn) conversations.
