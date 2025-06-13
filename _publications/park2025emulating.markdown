---
layout: publication
title: 'Emulating Retrieval Augmented Generation Via Prompt Engineering For Enhanced Long Context Comprehension In Llms'
authors: Joon Park, Kyohei Atarashi, Koh Takeuchi, Hisashi Kashima
conference: "Arxiv"
year: 2025
bibkey: park2025emulating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.12462"}
tags: ['RAG', 'Prompting', 'Reinforcement Learning']
---
This paper addresses the challenge of comprehending very long contexts in
Large Language Models (LLMs) by proposing a method that emulates Retrieval
Augmented Generation (RAG) through specialized prompt engineering and
chain-of-thought (CoT) reasoning. While recent LLMs support over 100,000 tokens
in a single prompt, simply enlarging context windows has not guaranteed robust
multi-hop reasoning when key details are scattered across massive input. Our
approach treats the model as both the retriever and the reasoner: it first tags
relevant segments within a long passage, then employs a stepwise CoT workflow
to integrate these pieces of evidence. This single-pass method thereby reduces
reliance on an external retriever, yet maintains focus on crucial segments. We
evaluate our approach on selected tasks from BABILong, which interleaves
standard bAbI QA problems with large amounts of distractor text. Compared to
baseline (no retrieval) and naive RAG pipelines, our approach more accurately
handles multi-fact questions such as object location tracking, counting, and
indefinite knowledge. Furthermore, we analyze how prompt structure, including
the order of question, relevant-text tags, and overall instructions,
significantly affects performance. These findings underscore that optimized
prompt engineering, combined with guided reasoning, can enhance LLMs'
long-context comprehension and serve as a lightweight alternative to
traditional retrieval pipelines.
