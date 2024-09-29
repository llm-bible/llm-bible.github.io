---
layout: publication
title: "Dialogue Chain-of-thought Distillation For Commonsense-aware Conversational Agents"
authors: Chae Hyungjoo, Song Yongho, Ong Kai Tzu-iunn, Kwon Taeyoon, Kim Minjin, Yu Youngjae, Lee Dongha, Kang Dongyeop, Yeo Jinyoung
conference: "Arxiv"
year: 2023
bibkey: chae2023dialogue
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.09343"}
tags: ['Agentic', 'Distillation', 'Efficiency And Optimization', 'RAG', 'Tools']
---
Human-like chatbots necessitate the use of commonsense reasoning in order to effectively comprehend and respond to implicit information present within conversations. Achieving such coherence and informativeness in responses however is a non-trivial task. Even for large language models (LLMs) the task of identifying and aggregating key evidence within a single hop presents a substantial challenge. This complexity arises because such evidence is scattered across multiple turns in a conversation thus necessitating integration over multiple hops. Hence our focus is to facilitate such multi-hop reasoning over a dialogue context namely dialogue chain-of-thought (CoT) reasoning. To this end we propose a knowledge distillation framework that leverages LLMs as unreliable teachers and selectively distills consistent and helpful rationales via alignment filters. We further present DOCTOR a DialOgue Chain-of-ThOught Reasoner that provides reliable CoT rationales for response generation. We conduct extensive experiments to show that enhancing dialogue agents with high-quality rationales from DOCTOR significantly improves the quality of their responses.
