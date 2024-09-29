---
layout: publication
title: Evaluating Very Long45;term Conversational Memory Of LLM Agents
authors: Maharana Adyasha, Lee Dong-ho, Tulyakov Sergey, Bansal Mohit, Barbieri Francesco, Fang Yuwei
conference: "Arxiv"
year: 2024
bibkey: maharana2024evaluating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.17753"}
tags: ['Agentic', 'Applications', 'Model Architecture', 'RAG']
---
Existing works on long45;term open45;domain dialogues focus on evaluating model responses within contexts spanning no more than five chat sessions. Despite advancements in long45;context large language models (LLMs) and retrieval augmented generation (RAG) techniques their efficacy in very long45;term dialogues remains unexplored. To address this research gap we introduce a machine45;human pipeline to generate high45;quality very long45;term dialogues by leveraging LLM45;based agent architectures and grounding their dialogues on personas and temporal event graphs. Moreover we equip each agent with the capability of sharing and reacting to images. The generated conversations are verified and edited by human annotators for long45;range consistency and grounding to the event graphs. Using this pipeline we collect LoCoMo a dataset of very long45;term conversations each encompassing 300 turns and 9K tokens on avg. over up to 35 sessions. Based on LoCoMo we present a comprehensive evaluation benchmark to measure long45;term memory in models encompassing question answering event summarization and multi45;modal dialogue generation tasks. Our experimental results indicate that LLMs exhibit challenges in understanding lengthy conversations and comprehending long45;range temporal and causal dynamics within dialogues. Employing strategies like long45;context LLMs or RAG can offer improvements but these models still substantially lag behind human performance.
