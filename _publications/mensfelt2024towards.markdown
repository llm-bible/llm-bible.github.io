---
layout: publication
title: 'Towards Logically Sound Natural Language Reasoning With Logic-enhanced Language Model Agents'
authors: Agnieszka Mensfelt, Kostas Stathis, Vince Trencsenyi
conference: "Arxiv"
year: 2024
bibkey: mensfelt2024towards
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2408.16081'}
tags: ['Agentic', 'GPT', 'Tools', 'Model Architecture', 'Reinforcement Learning']
---
Large language models (LLMs) are increasingly explored as general-purpose reasoners, particularly in agentic contexts. However, their outputs remain prone to mathematical and logical errors. This is especially challenging in open-ended tasks, where unstructured outputs lack explicit ground truth and may contain subtle inconsistencies. To address this issue, we propose Logic-Enhanced Language Model Agents (LELMA), a framework that integrates LLMs with formal logic to enable validation and refinement of natural language reasoning. LELMA comprises three components: an LLM-Reasoner, an LLM-Translator, and a Solver, and employs autoformalization to translate reasoning into logic representations, which are then used to assess logical validity. Using game-theoretic scenarios such as the Prisoner's Dilemma as testbeds, we highlight the limitations of both less capable (Gemini 1.0 Pro) and advanced (GPT-4o) models in generating logically sound reasoning. LELMA achieves high accuracy in error detection and improves reasoning correctness via self-refinement, particularly in GPT-4o. The study also highlights challenges in autoformalization accuracy and in evaluation of inherently ambiguous open-ended reasoning tasks.
