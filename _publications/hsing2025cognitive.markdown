---
layout: publication
title: 'MIRROR: Cognitive Inner Monologue Between Conversational Turns For Persistent Reflection And Reasoning In Conversational Llms'
authors: Nicole Hsing
conference: "Arxiv"
year: 2025
bibkey: hsing2025cognitive
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.00430"}
tags: ['Responsible AI', 'Model Architecture', 'RAG', 'GPT', 'Attention Mechanism']
---
Human intelligence relies on inner monologue to process complex information through simultaneous reflection, memory retrieval, and response formulation. We introduce MIRROR (Modular Internal Reasoning, Reflection, Orchestration, and Response), a cognitive architecture that systematically implements these parallel reasoning capabilities in large language models. MIRROR operates as a unified system with two distinct functional layers: the Thinker and the Talker. The Thinker encompasses: (1) the Inner Monologue Manager, coordinating reasoning threads across cognitive dimensions (Goals, Reasoning, and Memory); and (2) the Cognitive Controller, synthesizing these threads into a coherent internal narrative maintained across conversation turns. The Talker component then leverages this integrated narrative for context-aware responses. Evaluated on the CuRaTe benchmark--testing personalized dialogue with safety-critical constraints, conflicting preferences, and multi-turn consistency--LLMs utilizing the MIRROR architecture achieve up to 156% relative improvement in critical safety scenarios involving three persons with conflicting preferences, maintaining an average accuracy of ~>80% on all scenarios. Across scenario-specific comparisons, GPT-4o, Gemini 1.5 Pro, Claude 3.7 Sonnet, Llama 4 variants, and Mistral 3 variants with the MIRROR architecture outperformed baseline models by 21% on average (15.5 percentage points absolute). MIRROR directly addresses three critical LLM failure modes: sycophancy, attentional deficits to critical information, and inconsistent prioritization of conflicting constraints. This work bridges cognitive science and AI by implementing modular internal reasoning inspired by human cognition, creating a persistent internal model that significantly enhances multi-turn conversation capabilities.
