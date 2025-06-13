---
layout: publication
title: 'Llms Get Lost In Multi-turn Conversation'
authors: Philippe Laban, Hiroaki Hayashi, Yingbo Zhou, Jennifer Neville
conference: "Arxiv"
year: 2025
bibkey: laban2025llms
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.06120'}
tags: ['Reinforcement Learning', 'RAG']
---
Large Language Models (LLMs) are conversational interfaces. As such, LLMs have the potential to assist their users not only when they can fully specify the task at hand, but also to help them define, explore, and refine what they need through multi-turn conversational exchange. Although analysis of LLM conversation logs has confirmed that underspecification occurs frequently in user instructions, LLM evaluation has predominantly focused on the single-turn, fully-specified instruction setting. In this work, we perform large-scale simulation experiments to compare LLM performance in single- and multi-turn settings. Our experiments confirm that all the top open- and closed-weight LLMs we test exhibit significantly lower performance in multi-turn conversations than single-turn, with an average drop of 39% across six generation tasks. Analysis of 200,000+ simulated conversations decomposes the performance degradation into two components: a minor loss in aptitude and a significant increase in unreliability. We find that LLMs often make assumptions in early turns and prematurely attempt to generate final solutions, on which they overly rely. In simpler terms, we discover that *when LLMs take a wrong turn in a conversation, they get lost and do not recover*.
