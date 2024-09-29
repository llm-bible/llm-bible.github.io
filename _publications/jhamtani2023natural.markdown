---
layout: publication
title: "Natural Language Decomposition And Interpretation Of Complex Utterances"
authors: Jhamtani Harsh, Fang Hao, Xia Patrick, Levy Eran, Andreas Jacob, Van Durme Ben
conference: "Arxiv"
year: 2023
bibkey: jhamtani2023natural
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.08677"}
tags: ['Few Shot', 'In Context Learning', 'Prompting', 'Training Techniques']
---
Designing natural language interfaces has historically required collecting supervised data to translate user requests into carefully designed intent representations. This requires enumerating and labeling a long tail of user requests which is challenging. At the same time large language models (LLMs) encode knowledge about goals and plans that can help conversational assistants interpret user requests requiring numerous steps to complete. We introduce an approach to handle complex-intent-bearing utterances from a user via a process of hierarchical natural language decomposition and interpretation. Our approach uses a pre-trained language model to decompose a complex utterance into a sequence of simpler natural language steps and interprets each step using the language-to-program model designed for the interface. To test our approach we collect and release DeCU -- a new NL-to-program benchmark to evaluate Decomposition of Complex Utterances. Experiments show that the proposed approach enables the interpretation of complex utterances with almost no complex training data while outperforming standard few-shot prompting approaches.
