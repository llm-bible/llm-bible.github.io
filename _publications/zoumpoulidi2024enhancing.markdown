---
layout: publication
title: 'Bloomwise: Enhancing Problem-solving Capabilities Of Large Language Models Using Bloom''s-taxonomy-inspired Prompts'
authors: Maria-eleni Zoumpoulidi, Georgios Paraskevopoulos, Alexandros Potamianos
conference: "Arxiv"
year: 2024
bibkey: zoumpoulidi2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.04094"}
tags: ['RAG', 'Prompting']
---
Despite the continuous progress of Large Language Models (LLMs) across
various tasks, their performance on mathematical problems and reasoning tasks
remains limited. This limitation can be attributed, among other factors, to the
inherent difficulty of these problems and the fact that solutions often consist
of multiple steps, potentially of varying nature, making it challenging for a
single prompting technique to execute all required steps. To address this, we
introduce BloomWise, a new prompting technique, inspired by Bloom's Taxonomy,
aiming to improve LLMs' performance in solving such problems by encouraging
them to approach the problem starting from simple, i.e., remembering, and
progressing to higher cognitive skills, i.e., analyzing, until the correct
solution is reached. The decision regarding the need to employ more
sophisticated cognitive skills is based on self-evaluation performed by the
LLM. Thus, we encourage the LLM to deploy the appropriate cognitive processes.
In extensive experiments across 4 popular math reasoning datasets, we have
demonstrated the effectiveness of our proposed approach. We also present
extensive ablations, analyzing the strengths of each module within our system.
