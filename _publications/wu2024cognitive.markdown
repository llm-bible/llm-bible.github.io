---
layout: publication
title: Cognitive Llms Towards Integrating Cognitive Architectures And Large Language Models For Manufacturing Decision-making
authors: Wu Siyu, Oltramari Alessandro, Francis Jonathan, Giles C. Lee, Ritter Frank E.
conference: "Arxiv"
year: 2024
bibkey: wu2024cognitive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.09176"}
tags: ['Model Architecture', 'RAG', 'Tools']
---
Resolving the dichotomy between the human-like yet constrained reasoning processes of Cognitive Architectures and the broad but often noisy inference behavior of Large Language Models (LLMs) remains a challenging but exciting pursuit for enabling reliable machine reasoning capabilities in production systems. Because Cognitive Architectures are famously developed for the purpose of modeling the internal mechanisms of human cognitive decision-making at a computational level new investigations consider the goal of informing LLMs with the knowledge necessary for replicating such processes e.g. guided perception memory goal-setting and action. Previous approaches that use LLMs for grounded decision-making struggle with complex reasoning tasks that require slower deliberate cognition over fast and intuitive inference -- reporting issues related to the lack of sufficient grounding as in hallucination. To resolve these challenges we introduce LLM-ACTR a novel neuro-symbolic architecture that provides human-aligned and versatile decision-making by integrating the ACT-R Cognitive Architecture with LLMs. Our framework extracts and embeds knowledge of ACT-Rs internal decision-making process as latent neural representations injects this information into trainable LLM adapter layers and fine-tunes the LLMs for downstream prediction. Our experiments on novel Design for Manufacturing tasks show both improved task performance as well as improved grounded decision-making capability of our approach compared to LLM-only baselines that leverage chain-of-thought reasoning strategies.
