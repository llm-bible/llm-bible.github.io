---
layout: publication
title: 'Typos That Broke The Rag''s Back: Genetic Attack On RAG Pipeline By Simulating Documents In The Wild Via Low-level Perturbations'
authors: Sukmin Cho, Soyeong Jeong, Jeongyeon Seo, Taeho Hwang, Jong C. Park
conference: "Arxiv"
year: 2024
bibkey: cho2024typos
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.13948"}
tags: ['RAG', 'Security', 'Applications', 'Reinforcement Learning']
---
The robustness of recent Large Language Models (LLMs) has become increasingly
crucial as their applicability expands across various domains and real-world
applications. Retrieval-Augmented Generation (RAG) is a promising solution for
addressing the limitations of LLMs, yet existing studies on the robustness of
RAG often overlook the interconnected relationships between RAG components or
the potential threats prevalent in real-world databases, such as minor textual
errors. In this work, we investigate two underexplored aspects when assessing
the robustness of RAG: 1) vulnerability to noisy documents through low-level
perturbations and 2) a holistic evaluation of RAG robustness. Furthermore, we
introduce a novel attack method, the Genetic Attack on RAG (\textit\{GARAG\}),
which targets these aspects. Specifically, GARAG is designed to reveal
vulnerabilities within each component and test the overall system functionality
against noisy documents. We validate RAG robustness by applying our
\textit\{GARAG\} to standard QA datasets, incorporating diverse retrievers and
LLMs. The experimental results show that GARAG consistently achieves high
attack success rates. Also, it significantly devastates the performance of each
component and their synergy, highlighting the substantial risk that minor
textual inaccuracies pose in disrupting RAG systems in the real world.
